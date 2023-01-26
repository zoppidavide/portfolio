<template>
  <div class='row mt-5 mx-1 mx-lg-3 justify-content-between flex-sm-row flex-lg-row-reverse'>

    <div class='hero-img col-12 col-lg-6'>
      <div class='hero-img'>
        <img :src="thumbnail2" class="img-fluid"/>
      </div>
    </div>

    <div class='hero col-12 col-lg-5 mt-5 mt-lg-0'>
      <div class='KindaBigTitle'>
        {{ title2 }}
      </div>
      <div class='ReadableTextDefault pt-3'>
        {{ description2 }}
      </div>

      <div class='ReadableTextDefault pt-5'>
        <span class='bold'>Role:</span>
      </div>
      <div class='ReadableTextDefault'>
        {{ role2 }}
      </div>

      <div class='ReadableTextDefault pt-3'>
        <span class='bold'>Team:</span>
      </div>
      <div class='ReadableTextDefault'>
        {{ team2 }}
      </div>

      <div class='ReadableTextDefault pt-3 pb-5'>
        <a :href='to2' class='no-underline'> <div class='hover-underline-animation'> <span class='bold'> {{ link2 }}</span> </div> </a>
      </div>

      <div class=' '>
        <a href="#sezione"> <img src='~/assets/aarrooww.svg'> </a>
      </div>
    </div>

  </div>

</template>


<script>
export default {
  name: 'HeroProg',
  props: {
    title2: String,
    description2: String,
    role2: String,
    team2: String,
    to2: [String],
    link2: String,
    thumbnail2: String,
    tag1: String,
    tag2: String,
    tag3: String
  }
}
</script>


<style>
.hero {
  height: 75vh;
}

.hero-img {
  overflow: hidden;
  border-radius: 35px;
}

.hero-img img {
  width: 100%;
  object-fit: cover;
}
</style>
