<template>
  <div class='row row-projects mx-3'>
    <div class='col-4 col-custom'>
      <div class='card_project'>
        <div class='card_image1'>
          <img src="~/assets/AdOk_cover.png" class='img-fluid' alt='Responsive image' />
        </div>
        <div class='CardTitle'>
          AdOK: the future is handcrafted
        </div>
        <div class='CardText'>
          An interaction design project with the aim of revitalising Italian craftsmanship
        </div>
      </div>
    </div>

    <div class='col-4 col-custom'>
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
    </div>

    <div class='col-4 col-custom'>
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
  padding-top: 50px;
}

.card_project {

}

.card_image1 {
  /*background-image: url(~/assets/Disruptive_cover.png);*/
  background-color: #FFFBED;
  border-radius: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow:0px 0px 0px 2px black inset;
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

.card_image3 {
  /*background-image: url(~/assets/Disruptive_cover.png);*/
  background-color: #DDDDDD;
  border-radius: 30px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow:0px 0px 0px 2px black inset;
}

/*.image_project img {
  max-width: inherit;
}*/

</style>
