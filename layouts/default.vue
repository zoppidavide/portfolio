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
        {href: 'https://fonts.googleapis.com/css2?family=Red+Hat+Display:wght@600&display=swap',  rel: 'stylesheet'}
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

  .row-navbar {
    height: 80px;
    background-color: #ECE7E3;
  }

  .row-navbar-proj {
    height: 80px;
    background-color: #ECE7E3;
  }

  .row-info {
  }

  .row-progetti {
    padding-bottom: 100px;
    background-color: white;
    border-top-left-radius: 60px;
    border-top-right-radius: 60px;
    box-shadow: 0px 0px 50px 0px #C4C4C4;
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
    font-family: 'Red Hat Display', sans-serif;
  }

/*SMALL SIZE SCREEN (>481)*/

  @media screen and (max-width: 480px) {
    .BigAFTitle {
      font-family: 'RedHatDisplay-SemiBold';
      font-size: 32px;
      line-height: 36px;
      text-align: start;
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
    .testone {
      font-family: 'AkkuratLL-Light';
      font-size: 24px;
      line-height: 28px;
      padding-top: 3vh;
    }
    .row-heroabout {
      padding-top: 5vh;
    }
    .classprova {
      margin-top: 5vh;
      padding-top: 5vh;
      background-color: white;
      border-top-left-radius: 60px;
      border-top-right-radius: 60px;
      box-shadow: 0px 0px 50px 0px #C4C4C4;
    }
    .colonna-cv {
      margin-top: 5vh;
    }
    .row-herosection {
      height: 55vh;
    }
    .row-herosection2 {
      height: 25vh;
    }
  }

/*BIG SIZE SCREEN (<481)*/

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
    .testone {
      font-family: 'AkkuratLL-Light';
      font-size: 36px;
      line-height: 40px;
    }
    .row-heroabout {
      height: 85vh;
    }
    .classprova {
      background-color: white;
      border-top-left-radius: 60px;
      border-top-right-radius: 60px;
      box-shadow: 0px 0px 50px 0px #C4C4C4;
    }
    .colonna-cv {
      margin-top: 15vh;
    }
    .row-herosection {
      height: 45vh;
    }
    .row-herosection2 {
      height: 35vh;
    }
  }

  .EyecatchingTitle {
    font-family: 'RedHatDisplay-SemiBold';
    font-size: 36px;
  }

  .ReadableTextDefault {
    font-family: 'AkkuratLL-Light';
    font-size: 20px;
    line-height: 24px;
  }

  .ReadableText {
    font-family: 'AkkuratLL-Light';
    font-size: 20px;
    line-height: 24px;
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

  .black {
    color: #808080;
  }

  .huge {
    width: 300px;
    border: 2px solid #000000;
    color: #000000;
    border-radius: 45px;
    font-family: 'RedHatDisplay-SemiBold';
    font-size: 24px;
    background-color: #ECE7E3;
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

.hover-underline-animation {
  display: inline-block;
  font-family: 'AkkuratLL-Light';
  font-size: 20px;
  line-height: 22px;
  margin-top: 10px;
  margin-bottom: 20px;
  color: black;
  position: relative;
  /*color: var(--color-primary);*/
}

.hover-underline-animation:after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 2px;
  bottom: 0;
  left: 0;
  background-color: black;
  /*background-color: var(--color-primary);*/
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}

.hover-underline-animation:hover:after {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.huge2 {
  width: 300px;
  border: 2px solid #000000;
  color: #000000;
  border-radius: 45px;
  font-family: 'RedHatDisplay-SemiBold';
  font-size: 24px;
  background-color: #ECE7E3;
}

.no-underline {
  color: black;
}

.no-underline:hover {
  text-decoration: none;
  color: black;
}

.hover-underline-animation_2 {
  display: inline-block;
  font-family: 'RedHatDisplay-SemiBold';
  font-size: 36px;
  line-height: 22px;
  color: black;
  position: relative;
  /*color: var(--color-primary);*/
}

.hover-underline-animation_2:after {
  content: '';
  position: absolute;
  width: 100%;
  transform: scaleX(0);
  height: 4px;
  bottom: -4px;
  left: 0;
  background-color: black;
  /*background-color: var(--color-primary);*/
  transform-origin: bottom right;
  transition: transform 0.25s ease-out;
}

.hover-underline-animation_2:hover:after {
  transform: scaleX(1);
  transform-origin: bottom left;
}

</style>
