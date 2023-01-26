<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Negroni'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            THE SCIENCE BEHIND SOCIAL MEDIA
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The first output uses the complexity of a technical "blueprint"
            to illustrate Negronetto in all its parts, also exploiting the irony given
            by this type of analysis decontextualized. However, the keypoint remains
            to show the attention to detail behind a historic Negroni product
            such as this one.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/Negroni_1.png' class="img-fluid"/>
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
          <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/792811784?h=7e79885c60&autoplay=1&loop=1&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
        </div>
        <div class='col-5'>
          <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/792813345?h=86140e8654&autoplay=1&loop=1&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
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
  name: 'Negroni',
  data () {
    return {
      intro: {
        Negroni: {
          title2: 'NEGRONI',
          thumbnail2: require('~/assets/Negroni_0.png'),
          description2: 'Persona powered by sense is a fictional brand and product that want to...',
          role2: 'Project concept, storytelling, copywriting, web development',
          team2: 'Pietro Capra, Leonardo Puca',
          to2: "",
          link2: '',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Armani Silos',
          to3: "armanisilos"
        },
        Next: {
          next: 'AdOk: the future is handcrafted',
          to4: "adok"
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
