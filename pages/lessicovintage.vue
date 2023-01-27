<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.MagModa'/>

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
          <img src='~/assets/LessicoVintage_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/LessicoVintage_3.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/LessicoVintage_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/LessicoVintage_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10'>
          <img src='~/assets/LessicoVintage_7.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/LessicoVintage_6.png' class="img-fluid"/>
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
  name: 'Disruptive',
  data () {
    return {
      intro: {
        MagModa: {
          title2: 'LESSICO VINTAGE',
          thumbnail2: require('~/assets/LessicoVintage_1.png'),
          description2: 'Lessico Vintage is an online influencing project that showcases vintage and second-hand clothing. It documents stories, places and people, creating a guide for enthusiasts and beginners who would like to know about this reality.',
          role2: 'Team supervision, storytelling, UX/UI design',
          team2: 'Maria Nardi, Andrea Molteni, Elisabetta Vignali, Alice Belardinelli, Antonio Brunetti, Mattia Tafel, Andrea Benedetto, Laura Zani',
          to2: "https://www.instagram.com/lessicovintage/",
          link2: 'See the profile 🔗',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Preview & Pretest',
          to3: "previewpretest"
        },
        Next: {
          next: 'Persona',
          to4: "persona"
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
