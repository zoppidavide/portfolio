<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Persona'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            TAKING OFF EVERYONE'S MASK
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The persona kit is used in the main relational areas of everyone's life,
            so couple, family, friendship and work. The functioning of the kit is
            based on detecting the person's emotional state and comparing this
            information during a short call, at the end of which the system will
            be able to return a detailed report on the relationship, advising the
            user whether to maintain or terminate it. The procedure is designed to
            be repeated with a fixed cadence. With persona it is possible to take
            off daily masks and optimize your relational life.
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
          description2: 'Persona is a fictional narration where a product service is developed in order to ensure safe and lasting relationships for everyone. Persona allows anyone to leave the mask and see people that surrounds him without theirs.',
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
