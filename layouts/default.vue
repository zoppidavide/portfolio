<template>
  <div>
    <div class='container-fluid'>
      <LayoutNavbar />
    </div>
    <Nuxt/>
  </div>
</template>

<script>
export default {
  name: "DefaultLayout",
  head() {
    return {
      link: [
        {href: 'https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500&display=swap', rel: 'stylesheet'}
      ]
    }
  }
}
</script>


<style>

  body {
    background-color: #F6F2F2;
  }

  .btn-primary {
    width: 145px;
    background-color: black;
    border-radius: 30px;
    border-style: none;
    font-family: 'AkkuratLL-Bold';
    font-size: 16px;
  }

  .btn-primary:hover {
    opacity: 80%;
    width: 145px;
    background-color: black;
    border-radius: 30px;
    font-family: 'AkkuratLL-Bold';
    font-size: 16px;
  }

  .btn-outline-primary {
    width: 125px;
    opacity: 50%;
    border: 1px solid #000000;
    color: #000000;
    border-radius: 30px;
    text-decoration-color: black;
    font-family: 'AkkuratLL-Bold';
    font-size: 16px;
  }
  .row-navbar {
    height: 60px;
    background-color: #F5F3F1;
  }

  .row-herosection {
    height: 90vh;
  }

  .row-info {
    height: 110vh;
    background-color: white;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    box-shadow: 0px 0px 50px 0px #C4C4C4;
  }

  .colonna-cv {
    margin-top: 120px;
  }

  @font-face {
    font-family: "AkkuratLL-Bold";
    src: local("AkkuratLL-Bold"),
    url(/font/AkkuratLL-Bold.otf)
    format("opentype");
  }

  @font-face {
    font-family: "AkkuratLL-Light";
    src: local("AkkuratLL-Light"),
    url(/font/AkkuratLL-Light.otf)
    format("opentype");
  }

  @font-face {
    font-family: "RedHatDisplay-SemiBold";
    src: local("RedHatDisplay-SemiBold"),
    url(/font/RedHatDisplay-SemiBold.ttf)
    format("opentype");
  }

  .testone {
    font-family: 'AkkuratLL-Light';
    font-size: 36px;
    line-height: 40px;
  }

  .EyecatchingTitle {
    font-family: 'RedHatDisplay-SemiBold';
    font-size: 36px;
  }

  .ReadableText {
    font-family: 'AkkuratLL-Light';
    font-size: 20px;
    line-height: 22px;
    margin-top: 25px;
    margin-bottom: 50px;
  }

  .bold {
    font-family: AkkuratLL-Bold;
  }

</style>
