<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.MagModa'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            A PROCESS ANALYSIS<br>INSIDE THE MARKET
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The starting point of the project was the encounter with the company
            and its members. Since that moment the goal was to go inside the
            dynamics of the B2B fashion industry to fully understand the
            processes underneath.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/MagModa_1.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-7 alone'>
          <img src='~/assets/MagModa_2.png' class="img-fluid"/>
        </div>
        <div class='d-flex col-3 alone'>
          <img src='~/assets/MagModa_3.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            COMMUNICATING VALUES WITHIN A B2B
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The focus of our work was to understand the built-in value of the
            company and the elements of the supply chain where the competitive
            differential was located, and finally to decode this into a message
            to deliver to the prospect in a way that was relevant to him.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/MagModa_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_6.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_7.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            INSTAGRAM CHANNEL
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The touchpoint chosen to meet the prospect was instagram.  This was
            in order to intercept a certain segment of entrepreneurs in the
            fashion world, falling within our target audience. Thanks to a
            social channel, the user is led to discover the business, and to
            visit the website.
          </div>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/MagModa_13.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_8.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_10.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            THE CAMPAIGN LANDING PAGE
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The last part of this funnel is precisely the web page, where
            content is designed and sorted in such a way that a prospect
            has a way to view the offer in its completeness, but is also
            encouraged to continue learning about it, leaving a contact,
            which is the useful conversion to the company.
          </div>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/MagModa_14.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_11.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='col-10'>
          <div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/791945513?h=c7c153ceae&byline=0&portrait=0" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/MagModa_12.png' class="img-fluid"/>
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
          title2: 'MAG MODA',
          thumbnail2: require('~/assets/MagModa_0.png'),
          description2: 'Mag Moda is a small Italian company, active in the field of B2B fashion production, but also owning a little fashion brand. They needed a strategy for an efficient digital transition, empowering them to talk directly to their target.',
          role2: 'Team supervision, storytelling, UX/UI design',
          team2: 'Luca Dal Ben, Maria Nardi, Andrea Molteni, Elisabetta Vignali',
          to2: "/Analisi-Strategia.pdf",
          link2: 'Read the full documentation (ITA) 🔗',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Middle school Paolo VI',
          to3: "paolovi"
        },
        Next: {
          next: 'Preview & Pretest',
          to4: "previewpretest"
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
