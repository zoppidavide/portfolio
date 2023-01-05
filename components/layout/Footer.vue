<template>
  <div class='row row-footer mx-3'>
      <div class='col-4 col-footer'>
        <div class='EyecatchingTitle'>
          LET'S LINK
        </div>
        <img src = "~/assets/Pure_arrow.svg" alt="GoTo"/>
      </div>
    <div class='col-2 col-footer'>
      <div class='ReadableText'>
        LinkedIn
      </div>
    </div>
    <div class='col-2 col-footer'>
      <div class='ReadableText'>
        Instagram
      </div>
    </div>
    <div class='col-2 col-footer'>
      <div class='ReadableText'>
        Telegram
      </div>
    </div>
    <div class='col-2 col-footer'>
      <div class='ReadableText'>
        Privacy
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style>

.row-footer {
  height: 200px;
  /*border-top-left-radius: 60px;
  border-top-right-radius: 60px;*/
}

.col-footer {
  margin-top: 35px;
}

</style>
