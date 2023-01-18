<template>
  <NuxtLink :to='to4' class='no-underline'>
    <div class='freccine d-flex justify-content-end'>

      <div class='mx-3'>
        <div class='ReadableTextDefault' style='text-align: right'>
          Next project
        </div>
        <div class='ReadableTextDefault hover-underline-animation_3' style='text-align: right'>
          <span class='bold'> {{ next }} </span>
        </div>
      </div>

      <div class='align-items-center d-flex'>
        <img src='~/assets/arrow_right.svg' class="img-fluid"/>
      </div>

    </div>
  </NuxtLink>
</template>


<script>
export default {
  name: 'Next',
  props: {
    next: String,
    to4: [String]
  }
}
</script>


<style>
.freccine {
  width: 40vw;
  color: black;
}
</style>
