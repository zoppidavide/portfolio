<template>
  <div class='row row-footer mx-3'>
      <div class='col-4 col-footer'>
        <div class='EyecatchingTitle'>
          LET'S LINK
        </div>
        <img src = "~/assets/Pure_arrow.svg" alt="GoTo"/>
      </div>
    <div class='col-2 col-footer'>
      <a href="https://www.linkedin.com/in/davide-zoppi-396462209/" class='no-underline'> <div class='ReadableText'>
        LinkedIn
      </div> </a>
    </div>
    <div class='col-2 col-footer'>
      <a href="https://www.instagram.com/dazonnnn/" class='no-underline'> <div class='ReadableText'>
        Instagram
      </div> </a>
    </div>
    <div class='col-2 col-footer'>
      <a href="https://t.me/dazonnnnn" class='no-underline'> <div class='ReadableText'>
        Telegram
      </div> </a>
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
  /*background-color: #ECE7E3;*/
  /*border-top-left-radius: 60px;
  border-top-right-radius: 60px;*/
}

.col-footer {
  margin-top: 35px;
}

</style>
