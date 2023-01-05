<template>
  <div>

    <div class="aboutmephoto mt-4">

      <img src="~/assets/carlo.jpg" />

    </div>



<!--    <div class="mx-2 mt-2">
      <b-row class="">

        <b-col cols="3" class=" p-0">
          <div class="socialboxsm m-2 "> <img src="~static/images/aboutme/mail.svg" /> </div>
        </b-col>

        <b-col cols="3" class=" p-0">
          <div class="socialboxsm m-2 "> <a href="https://www.linkedin.com/in/giovanniclericetti/" target="_blank"> <img src="~static/images/aboutme/linkedin.svg" />  </a> </div>
        </b-col>

        <b-col cols="3" class=" p-0">
          <div class="socialboxsm m-2 "> <a href="https://t.me/giovanniclericetti" target="_blank"> <img src="~static/images/aboutme/telegram.svg" /> </a> </div>
        </b-col>

        <b-col cols="3" class=" p-0">
          <div class="socialboxsm m-2 "> <a href="https://www.instagram.com/giovanniclericetti.png/" target="_blank"> <img src="~static/images/aboutme/instagram.svg" /> </a> </div>
        </b-col>

      </b-row>
    </div></div>-->
  </div>
</template>

<script>
export default {
  name: "AboutPhoto",
}
</script>

<style>
.aboutmephoto{
  border-radius: 20px;
  overflow: hidden;
  max-height: 550px;
}
.aboutmephoto img{
  max-width: inherit;
  max-height: inherit;
  height: inherit;
  width: inherit;
  object-fit: cover;
}
</style>
