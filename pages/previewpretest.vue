<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.PreviewPretest'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            SCALING AN IDENTITY TO FIT SPECIFIC NEEDS
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The challenge of such an event is continuity that must be maintained
            over the years in the brand and the production recognizability, but
            allowing it to be scaled up to meet new needs.
            The event is distinguished by its many variations over the years,
            leading to a number of different outputs capable of carrying forward
            the message of the Preview and Pretest.
          </div>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/PreviewPretest_1.jpg' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='col-10'>
          <div class='row'>
            <div class='alone col-12 col-lg-4'>
              <img src='~/assets/PreviewPretest_2.png' class="img-fluid"/>
            </div>
            <div class='alone col-12 col-lg-8'>
              <img src='~/assets/PreviewPretest_3.png' class="img-fluid"/>
            </div>
          </div>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/PreviewPretest_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/PreviewPretest_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/PreviewPretest_6.png' class="img-fluid"/>
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
  name: 'PreviewPretest',
  data () {
    return {
      intro: {
        PreviewPretest: {
          title2: 'PREVIEW & PRETEST',
          thumbnail2: require('~/assets/PreviewPretest_0.jpg'),
          description2: 'Preview & Pretest is a series of events dedicated to future design & architecture students at Politecnico di Milano. Preview is an event in which students projects are presented in order to help them in the choice of the academic course. Pretest is a three-day study event in preparation to the admission test.',
          role2: 'Brand identity, team leading, event design',
          team2: 'Giovanni Clericetti, Tommaso Prinetti',
          to2: "https://disruptive.meetingrimini.org/",
          link2: 'Visit the Instagram 🔗',
        }
      },

      link: {
        Previous: {
          previous: 'MagModa: a SME digital transformation',
          to3: "magmoda"
        },
        Next: {
          next: 'Lessico Vintage',
          to4: "lessicovintage"
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
