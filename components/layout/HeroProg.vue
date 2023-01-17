<template>
  <div class='row mt-5'>
    <div class='hero col-12 col-lg-6'>
      <div class='KindaBigTitle'>
        {{ title }}
      </div>

      <div class='CardTitle'>
        {{ title }}
      </div>

      <div class='CardText'>
        {{ bio }}
      </div>
  </div>

  </div>

</template>


<script>
export default {
  name: 'HeroProg',
  props: {
    title: String,
    description: String,
    role: String,
    team: String,
    thumbnail: String,
    tag1: String,
    tag2: String,
    tag3: String
  }

}
</script>


<style>

</style>
