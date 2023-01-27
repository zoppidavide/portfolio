<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Persona'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            THE SCIENCE BEHIND SOCIAL MEDIA
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
          <img src='~/assets/Persona_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/Persona_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10'>
          <img src='~/assets/Persona_3.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/Persona_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/Persona_6.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='col-5'>
          <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/792811784?h=7e79885c60&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
        </div>
        <div class='col-5'>
          <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/792813345?h=86140e8654&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
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
  name: 'Persona',
  data () {
    return {
      intro: {
        Persona: {
          title2: 'PERSONA',
          thumbnail2: require('~/assets/Persona_1.png'),
          description2: 'Persona powered by sense is a fictional brand and product that want to...',
          role2: 'Project concept, storytelling, copywriting, web development',
          team2: 'Anna Cattaneo, Pietro Capra, Simone Inverardi, Leonardo Puca',
          to2: "",
          link2: '',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Lessico Vintage',
          to3: "lessicovintage"
        },
        Next: {
          next: 'Armani Silos',
          to4: "armanisilos"
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
