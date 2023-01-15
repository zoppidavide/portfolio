<template>
  <div>
    <div class='container-fluid'>
<!--      <LayoutNavbar />-->
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

html {
  scroll-behavior: smooth;
}

  body {
    background-color: #ECE7E3;
  }

.row-heroabout {
  height: 85vh;
}

  .row-navbar {
    height: 80px;
    background-color: #ECE7E3;
  }

  .row-herosection {
    height: 45vh;
  }

.row-herosection2 {
  height: 35vh;
}

  .row-info {
  }

  .classprova {
    height: 110vh;
    background-color: white;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    box-shadow: 0px 0px 50px 0px #C4C4C4;
  }

  .row-progetti {
    padding-bottom: 100px;
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

  @media screen and (max-width: 480px) {
    .BigAFTitle {
      font-family: 'RedHatDisplay-SemiBold';
      font-size: 32px;
      line-height: 36px;
      text-align: center;
    }

    .KindaBigTitle {
      font-family: 'RedHatDisplay-SemiBold';
      font-size: 32px;
      line-height: 36px;
    }

    .CardTitle {
      font-family: 'AkkuratLL-Bold';
      margin-top: 15px;
      font-size: 20px;
      line-height: 22px;
      color: black;
    }

    .CardText {
      font-family: 'AkkuratLL-Light';
      font-size: 18px;
      line-height: 22px;
      margin-top: 5px;
      color: #808080;
    }

  }

  @media screen and (min-width: 481px) {
    .BigAFTitle {
      font-family: 'RedHatDisplay-SemiBold';
      font-size: 48px;
      line-height: 56px;
      text-align: center;
    }

    .KindaBigTitle {
      font-family: 'RedHatDisplay-SemiBold';
      font-size: 48px;
      line-height: 56px;
    }

    .CardTitle {
      font-family: 'AkkuratLL-Bold';
      margin-top: 20px;
      font-size: 20px;
      line-height: 22px;
      color: black;
    }

    .CardText {
      font-family: 'AkkuratLL-Light';
      font-size: 18px;
      line-height: 22px;
      margin-top: 10px;
      color: #808080;
    }

  }

  .EyecatchingTitle {
    font-family: 'RedHatDisplay-SemiBold';
    font-size: 36px;
  }

  .ReadableTextDefault {
    font-family: 'AkkuratLL-Light';
    font-size: 20px;
    line-height: 22px;
  }

  .ReadableText {
    font-family: 'AkkuratLL-Light';
    font-size: 20px;
    line-height: 22px;
    margin-top: 25px;
    margin-bottom: 50px;
    color: black;
  }

  .CardTitle:link, .CardTitle:hover, .CardTitle:visited, .CardTitle:active {
    text-decoration: none;
    color: black;
  }


  .CardText:link, .CardText:hover, .CardText:visited, .CardText:active {
    text-decoration: none;
    color: #808080;
  }

  .bold {
    font-family: AkkuratLL-Bold;
  }

  .huge {
    width: 300px;
    border: 2px solid #000000;
    color: #000000;
    border-radius: 45px;
    font-family: 'RedHatDisplay-SemiBold';
    font-size: 24px;
    background-color: white;
  }

.huge:hover {
  width: 300px;
  border: 2px solid #000000;
  color: #FFFFFF;
  border-radius: 45px;
  font-family: 'RedHatDisplay-SemiBold';
  font-size: 24px;
  background-color: black;
}

 .huge span.icon-arrow {
  background: url(~/assets/ddown.svg) no-repeat;
  float: left;
  height: 36px;
  width: 26px;
  margin-left: 10px;
 }

.huge:hover span.icon-arrow {
  background: url(~/assets/ddown-white.svg) no-repeat;
}

</style>
