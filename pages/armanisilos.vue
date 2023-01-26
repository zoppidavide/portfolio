<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.ArmaniSilos'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            NARRATING ARMANI AND THE COLLECTION "ETNIE"
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            We started by researching popular
            trends and topics in our target audience's interests, and use that
            to craft a unique and engaging account. Through a combination
            of organic content creation and strategic collaborations with events, shops
            and other accounts, we were able to rapidly build a following. Within
            the two months duration of the projects our account reached over 3000 followers and
            was consistently enhancing his numbers and visibility.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/ArmaniSilos_1.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='col-10'>
            <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/720251321?h=e1868ebc44&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10'>
          <img src='~/assets/ArmaniSilos_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='row mx-3 mt-5'>

        <div class='col-12 mt-5 d-flex justify-content-between'>
          <LayoutPrevious v-bind='link.Previous' />
          <LayoutNext v-bind='link.Next' />
        </div>

      </div>

    </div>

    <LayoutFooter />

  </div>

</template>


<script>
export default {
  name: 'ArmaniSilos',
  data () {
    return {
      intro: {
        ArmaniSilos: {
          title2: 'ARMANI SILOS',
          thumbnail2: require('~/assets/ArmaniSilos_0.png'),
          description2: 'The goal of the project, starting with the choice of a museum environment to work on, was to improve its accessibility for people with vision- and hearing-related disabilities, proposing an alternative route to learn about Armani Silos and explore its beauty.',
          role2: 'Project concept, motion-graphic, video-editing',
          team2: 'Deborah Franceschini, Nicole Guattini, Francesco Ricciardi, Marta Coppola',
          to2: "",
          link2: '',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Persona',
          to3: "persona"
        },
        Next: {
          next: 'Negroni',
          to4: "negroni"
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
