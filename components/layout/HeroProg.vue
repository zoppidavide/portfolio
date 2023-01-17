<template>
  <div class='row mt-5'>
    <div class='hero col-12 col-lg-6'>
      <div class='KindaBigTitle'>
        {{ title2 }}
      </div>

      <div class=''>
        {{ title2 }}
      </div>

      <div class=''>
        {{  }}
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
    thumbnail2: String,
    tag1: String,
    tag2: String,
    tag3: String
  }

}
</script>


<style>

</style>
