<template>
  <div class='row row-footer mx-1 mx-lg-3 mt-3'>
      <div class='d-flex col-12 col-lg-8 col-footer-1'>
        <div>
          <a href="mailto:zoppi.davide7@gmail.com" class='no-underline'>
            <button class="BigButton"><span>LET'S WORK TOGETHER</span></button>
          </a>
        </div>
      </div>

    <div class='col-12 col-lg-4'>
      <div class='row mt-1'>
        <div class='col-12 col-lg-4 col-footer-2'>
          <a href="https://www.linkedin.com/in/davide-zoppi-396462209/" class='no-underline'> <div class='hover-underline-animation'>LinkedIn</div> </a>
        </div>
        <div class='col-12 col-lg-4 col-footer'>
          <a href="https://www.instagram.com/dazonnnn/" class='no-underline'> <div class='hover-underline-animation'>Instagram</div> </a>
        </div>
        <div class='col-12 col-lg-4 col-footer'>
          <a href="https://t.me/dazonnnnn" class='no-underline'> <div class='hover-underline-animation'>Telegram</div> </a>
        </div>
      </div>
    </div>

    <div class='ReadableTextDefault col-12 pt-5 my-2' style='color: #808080; font-size: 16px; text-align: center'>
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
}

.col-footer {
}

@media screen and (min-width: 481px) {
  .BigButton {
    background-color: transparent;
    border: none;
    color: black;
    transition: all 0.5s;

    font-family: RedHatDisplay-SemiBold;
    font-size: 36px;
    text-align: left;
  }
}

@media screen and (max-width: 480px) {
  .BigButton {
    background-color: transparent;
    border: none;
    color: black;
    transition: all 0.5s;
    padding-bottom: 30px;

    font-family: RedHatDisplay-SemiBold;
    font-size: 24px;
    text-align: left;
  }
}

.BigButton span {
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.BigButton span:after {
  content: url("~/assets/Pure_arrow.svg");
  position: absolute;
  opacity: 0;
  top: 0;
  right: -45px;
  transition: 0.5s;
}

.BigButton:hover span {
  padding-right: 55px;
}

.BigButton:hover span:after {
  opacity: 1;
  right: 0;
}


</style>
