<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Disruptive'/>

    <div id="sezione" class='row-progetto'>

      <div class='justify-content-center d-lg-flex' style='padding-top: 150px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            RE-THINKING DIGITAL<br>EXHIBITION STANDARDS
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            Visual, experience and experiential design seamlessly blend with storytelling giving birth to an engaging and fascinating 360º experience.<br>
            Thanks to original content, such as illustrations, video-interviews and other digital content, Disruptive is a completely new way of exploring and approaching the great rebuilding challenge that awaits.
          </div>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/disruptive_2.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='d-flex col-10'>
          <img src='~/assets/disruptive_3.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-lg-flex'>
        <div class='alone d-flex col-10'>
          <img src='~/assets/disruptive_5.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='alone d-flex col-10'>
          <img src='~/assets/disruptive_4.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='col-10'>
         <div class='row'>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_9.png' class="img-fluid"/>
          </div>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_10.png' class="img-fluid"/>
          </div>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_11.png' class="img-fluid"/>
          </div>
         </div>
          <div class='row mt-4'>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_12.png' class="img-fluid"/>
          </div>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_13.png' class="img-fluid"/>
          </div>
          <div class='alone_sm col-6 col-lg-4'>
            <img src='~/assets/disruptive_14.png' class="img-fluid"/>
          </div>
         </div>
        </div>
      </div>

      <div class='justify-content-center d-lg-flex mt-5' style='padding-top: 100px;'>
        <div class='col-12 col-lg-5'>
          <div class='EyecatchingTitle mx-1 mx-lg-3'>
            NARRATORS FOR<br>A GREAT STORY
          </div>
          <div class='ReadableTextDefault mt-3 mt-lg-5 mx-1 mx-lg-3'>
            The project was designed during the pandemic. As Covid-19 restrictions ceased,
            we were also able to bring our project to a phisical exhibibition at Riminifiera, designing
            a space to present the interviews and the life of Sergio Marchionne.
          </div>
        </div>
<!--        <div class='col-12 col-lg-5'>
           video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>-->
        <div class='col-12 col-lg-5'>
          <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item interview" src="https://www.youtube.com/embed/VSNttCMVKhg" allowfullscreen></iframe>
          </div>
        </div>

      </div>

      <div class='justify-content-center d-lg-flex alone_sm mt-3'>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/disruptive_6.png' class="img-fluid"/>
        </div>
        <div class='col-12 col-lg-5'>
          <img src='~/assets/disruptive_7.png' class="img-fluid"/>
        </div>
      </div>

      <div class='col-12 justify-content-center align-items-center mt-3 mt-lg-5 d-flex'>
        <div class='d-flex col-10'>
          <img src='~/assets/disruptive_8.png' class="img-fluid"/>
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
          title2: 'DISRUPTIVE',
          thumbnail2: require('~/assets/disruptive_1.jpg'),
          description2: '"The challenge of rebuilding" is a design-centered digital first exhibition born in 2020 from a group of university students, while facing the uncertainties of a generation looking ahead.',
          role2: 'Project concept, UX/UI, storytelling, copy-writing',
          team2: 'Federico Pozzi, Marco Pari, Andrea Silvano, Giovanni Clericetti, Alice Bocchio, Michele Bruno',
          to2: "https://disruptive.meetingrimini.org/",
          link2: 'Visit the website︎ 🔗',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2',
        }
      },

      link: {
        Previous: {
          previous: 'AdOk: the future is handcrafted',
          to3: "about"
        },
        Next: {
          next: 'Middle school Paolo VI',
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
