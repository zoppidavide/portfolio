<template>
<!--    <div
      :style="{ backgroundColor: `hsl(${x}, 80%, 50%)` }"
      class="movearea"
      @mousemove="onMousemove"
    >-->
<!--      <p>Move your mouse across this div...</p>
      <p>x: {{ x }}</p>-->

      <div class='row mx-1 mx-lg-3 row-herosection align-items-end d-flex justify-content-center'>
          <div class='BigAFTitle'>
            Hi, I’m Davide! An italian <span
:style="{ color: `hsl(${x}, 80%, 50%)` }"
            class="movearea"
            @mousemove="onMousemove">communication<br>
            and experience designer</span>, currently enrolled<br>
            in Communication Design master degree at Polimi<br>
          </div>
        </div>

</template>


<script>
export default {
  name: 'Nicetomeetyou',

  data() {
  return {
    x: 0
  }
},
methods: {
  onMousemove(e) {
    this.x = e.clientX
  }
}
}
</script>


<style>
.movearea {
  transition: 0.3s background-color ease;
}
</style>
