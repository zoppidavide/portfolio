<template>
  <div class='card'>
    <NuxtLink :to='to' class='no-underline'>

      <div class='card_image' style='background-color: var(--color-secondary);'>
<!--        <img src="~/assets/Disruptive_cover.png" class='img-fluid' alt='Responsive image' />-->
        <img :src="thumbnail" class="img-fluid"/>
      </div>

      <div class='CardTitle'>
        {{ title }}
      </div>

      <div class='CardText'>
        {{ bio }}
      </div>

    </NuxtLink>
  </div>

</template>


<script>
export default {
  name: 'CardNew',
  props: {
    title: String,
    thumbnail: String,
    bio: String,
    to: [String]
  }
}
</script>


<style>

.card {
  border: none;
  color: black;
}

.card_image {
  /*background-color: #458FDA;*/
  border-radius: 35px;
  position: relative;
  overflow: hidden;
  border: 1px solid #000000;
  box-shadow: 0px 3px 10px 1px #b6b6b6;

}

.card_image {
  width: 100%;
  object-fit: cover;
}

.card img {
  transition: transform 0.3s ease-in-out;
}

.card:hover img {
  transform: scale(1.04);
}

</style>
