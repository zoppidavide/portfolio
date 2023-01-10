<template>
  <div class='row row-projects mx-1 mx-lg-3 pt-5'>
    <div class='col-sm-12 col-lg-4 col-custom pt-5'>
      <b-link to="about" class='no-underline'>
      <div class='card_project_1'>
        <div class='card_image_1'>
          <img src="~/assets/AdOk_thumbnail.png" class='img-fluid' alt='Responsive image' />
        </div>
        <div class='CardTitle'>
          AdOK: the future is handcrafted
        </div>
        <div class='CardText'>
          An interaction design project with the aim of revitalising Italian craftsmanship
        </div>
      </div>
      </b-link>
    </div>

    <div class='col-sm-12 col-lg-4 col-custom pt-5'>
      <b-link to="about">
      <div class='card_project'>
        <div class='card_image2'>
          <img src="~/assets/Disruptive_cover.png" class='img-fluid' alt='Responsive image' />
        </div>
        <div class='CardTitle'>
          Disruptive: the challenge of rebuilding
        </div>
        <div class='CardText'>
          A digital first exhibition born in 2020 portraying Sergio Marchionne's life at Fiat
        </div>
      </div>
      </b-link>
    </div>

    <div class='col-sm-12 col-lg-4 col-custom pt-5'>
      <div class='card_project'>
        <div class='card_image3'>
          <img src="~/assets/PaoloVI_cover.png" class='img-fluid' alt='Responsive image' />
        </div>
        <div class='CardTitle'>
          Middle School Paolo VI
        </div>
        <div class='CardText'>
          An elaborate communication project for a school that includes renewed brand identity and website
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'Projects'
}
</script>

<style>

.row-projects {
  height: 200px;
}

.card_project {
  color: black;
}

.card_project_1 {
  color: black;
}

.no-underline:hover {
  text-decoration: none;
}

.card_image_1 {
  /*background-image: url(~/assets/Disruptive_cover.png);*/
  background-color: #FFFBED;
  border-radius: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow:0px 0px 0px 2px black inset;
}

.card_project_1 img {
  transition: transform 0.3s ease-in-out;
}

.card_project_1:hover img {
  transform: scale(1.04);
}



.card_image2 {
  /*background-image: url(~/assets/Disruptive_cover.png);*/
  background-color: #458FDA;
  border-radius: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow:0px 0px 0px 2px black inset;
}

.card_image2 img {
  transition: transform 0.3s ease-in-out;
}

.card_image2 img:hover {
  transform: scale(1.04);
}

.card_image3 {
  /*background-image: url(~/assets/Disruptive_cover.png);*/
  background-color: #DDDDDD;
  border-radius: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow:0px 0px 0px 2px black inset;
}

.card_image3 img {
  transition: transform 0.3s ease-in-out;
}

.card_image3 img:hover {
  transform: scale(1.04);
}

/*.image_project img {
  max-width: inherit;
}*/

</style>
