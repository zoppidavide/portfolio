<template>
  <NuxtLink :to='to3' class='no-underline'>
    <div class='freccine d-flex'>
      <div class='align-items-center d-flex'>
        <img src='~/assets/arrow_left.svg' class="img-fluid"/>
      </div>
      <div class='mx-3'>
        <div class='ReadableTextDefault'>
          Previous project
        </div>
        <div class='ReadableTextDefault hover-underline-animation_3'>
          <span class='bold'> {{ previous }} </span>
        </div>
      </div>

    </div>
  </NuxtLink>
</template>


<script>
  export default {
    name: 'Previous',
    props: {
      previous: String,
      to3: [String]
    }
  }
</script>


<style>
.freccine {
  width: 40vw;
  color: black;
}
</style>
