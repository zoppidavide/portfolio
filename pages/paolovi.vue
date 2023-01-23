<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Disruptive'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            A NEW SET OF CORE VALUES
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            Visual, experience and experiential design seamlessly blend with storytelling giving birth to an engaging and fascinating 360º experience.<br>
            Thanks to original content, such as illustrations, video-interviews and other digital content, Disruptive is a completely new way of exploring and approaching the great rebuilding challenge that awaits.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/PaoloVI_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/PaoloVI_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='col-10'>
          <div class='row'>
            <div class='alone_sm col-12 col-lg-6'>
              <img src='~/assets/PaoloVI_6.png' class="img-fluid"/>
            </div>
            <div class='alone_sm col-12 col-lg-6'>
              <img src='~/assets/PaoloVI_7.png' class="img-fluid"/>
            </div>
          </div>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            RENEWING THE SCHOOL PRESENCE ONLINE
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            Visual, experience and experiential design seamlessly blend with storytelling giving birth to an engaging and fascinating 360º experience.<br>
            Thanks to original content, such as illustrations, video-interviews and other digital content, Disruptive is a completely new way of exploring and approaching the great rebuilding challenge that awaits.
          </div>
        </div>
        <div class='col-12 col-lg-5 alone'>
          <img src='~/assets/PaoloVI_9.png' class="img-fluid"/>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-3 mt-lg-5'>
        <div class='d-flex col-10 alone'>
          <img src='~/assets/PaoloVI_8.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='col-10'>
          <div class='row'>
            <div class='alone col-12 col-lg-5'>
              <img src='~/assets/PaoloVI_10.png' class="img-fluid"/>
            </div>
            <div class='alone col-12 col-lg-7'>
              <img src='~/assets/PaoloVI_11.png' class="img-fluid"/>
            </div>
          </div>
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
        Disruptive: {
          title2: 'PAOLO VI',
          thumbnail2: require('~/assets/PaoloVI_4.png'),
          description2: 'Paolo VI Middle School is a private school located just outside of Milan, Italy. They are currently going through a systemic renovation and they need to connect with people through functional channels.',
          role2: 'Brand identity, UX/UI design',
          team2: 'Tommaso Prinetti, Michele Bruno',
          to2: "https://disruptive.meetingrimini.org/",
          link2: 'Visit the website︎ 🔗',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'Disruptive: the challenge of rebuilding',
          to3: "disruptive"
        },
        Next: {
          next: 'Mag Moda: a SME digital transformation',
          to4: "about"
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
