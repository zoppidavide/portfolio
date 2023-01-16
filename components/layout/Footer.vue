<template>
  <div class='row row-footer mx-3'>
      <div class='col-8 col-footer d-flex align-items-start justify-content-start'>
        <div class='EyecatchingTitle'> <a href="https://t.me/dazonnnnn" class='no-underline'>
          LET'S LINK
        </a> </div>
        <div class='freccia mt-2'> <a href="https://t.me/dazonnnnn" class='no-underline'>
          <img src = "~/assets/Pure_arrow.svg" alt="GoTo"/>
        </a> </div>
      </div>

    <div class='col-4'>
      <div class='row'>
        <div class='col-4 col-footer'>
          <a href="https://www.linkedin.com/in/davide-zoppi-396462209/" class='no-underline'> <div class='hover-underline-animation'>LinkedIn</div> </a>
        </div>
        <div class='col-4 col-footer'>
          <a href="https://www.instagram.com/dazonnnn/" class='no-underline'> <div class='hover-underline-animation'>Instagram</div> </a>
        </div>
        <div class='col-4 col-footer'>
          <a href="https://t.me/dazonnnnn" class='no-underline'> <div class='hover-underline-animation'>Telegram</div> </a>
        </div>
      </div>
    </div>

    <div class='ReadableText col-12' style='color: #808080; font-size: 16px'>
      @ 2023 Davide Zoppi, portfolio
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

.freccia {
  height: 36px;
  padding-left: 20px;
}

</style>
