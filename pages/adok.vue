<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.AdOk'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            TODAY'S ARTISANS<br>
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The first phase of the project was a field reaserch and a desk research involving many artisans and possible users
            with interviews, online forms and tracing habits. The purpose of this part was to collect information
            and produce insights in order to understand how to connect the analyzed category with its audience effectively.
          </div>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/AdOk_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/AdOk_3.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            APP FOR USERS<br>
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The native mobile application offer to the users a unique way to explore and discover
            the shops near them. The app features include a personalized feed tailored to your interests,
            a map of local artisans, and an in-app marketplace for to buy unique handmade
            items and experiences.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/AdOk_6.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-4 mt-lg-4 d-flex'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/AdOk_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg- d-flex'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/AdOk_5.png' class="img-fluid"/>
        </div>
      </div>


      <div class='row mx-3 mt-5'>

        <div class='col-12 mt-5 d-flex justify-content-end'>
<!--          <LayoutPrevious v-bind='link.Previous' />-->
          <LayoutNext v-bind='link.Next' />
        </div>

      </div>

    </div>

    <LayoutFooter />

  </div>

</template>


<script>
export default {
  name: 'Disruptive',
  data () {
    return {
      intro: {
        AdOk: {
          title2: 'AdOk',
          thumbnail2: require('~/assets/AdOk_1.png'),
          description2: 'The future is handcrafted. An interaction design project that brings new generations closer to the artisans working in our cities, providing them with a guide to discover, learn about and buy from them.',
          role2: 'Project concept, UX/UI, copy-writing, web-development',
          team2: 'Olimpia Di Via, Deborah Franceschini, Tazio Emanuele Furiani, Simone Gigante, Camilla Guerci, Giulia Picasso, Luca Vanetti',
          to2: "https://zoppidavide.github.io/AdOk/index.html",
          link2: 'Visit the project website︎ 🔗',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Next: {
          next: 'Disruptive: the challenge of rebuilding',
          to4: "disruptive"
        }
      }
    }
  }
}
</script>

<style>

.alone img {
  border-radius: 35px;
}

.alone_sm img {
  border-radius: 15px;
}

.interview {
  border-radius: 15px;
}

.shadow {
  box-shadow: 0 0 20px 0 black;
}

</style>
