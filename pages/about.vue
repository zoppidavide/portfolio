<template>
  <div class='container-fluid'>

    <LayoutNavbarAbout />

    <div class='row row-heroabout align-items-center mx-1 mx-lg-3'>
      <div class="col-12 col-lg-8">
        <div class='testone'>Hi! I’m Davide Zoppi, a 23 yo Italian communication and experience designer, based in Milan, Italy. Currently I’m enrolled in the last year of Communication Design master degree at Politecnico di Milano.<br>
          <br>During my years of study, I became very attached to design as a discipline and to the design process. The design culture has become an important part of the way I do things, capable of permeating every aspect of my life.
          In the design field I believe that teamwork is of fundamental importance, making possible to match different perspectives and experiences, leading to well-rounded solutions.
        </div>
      </div>
      <div class="col-12 col-lg-4">
        <LayoutAboutPhoto />
      </div>
    </div>

    <div class='container-fluid classprova'>
      <div class='row row-info mx-1 mx-lg-3'>
      <div class='col-12 col-lg-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          EXPERIENCES
        </div>
        <div class='ReadableText'>
          <span class="black">March 2022 - October 2022</span><br>
          Motion and graphic design intern<br>
          at Politecnico di Milano<br>
          <br>
          <span class="black">September 2021 - October 2022</span><br>
          UX Design and branding<br>
          at Paolo VI secondary school<br>
          <br>
          <span class="black">June 2020 - December 2020</span><br>
          Motion designer and social media<br>
          content creation at Storytel<br>
          <br>
          <span class="black">September 2019 - October 2020</span><br>
          Motion designer for Ziio Jewels<br>
        </div>
        <a href="/DavideZoppi-CV.pdf" class='no-underline'>
          <button class="BigButton"><span>DOWNLOAD CV</span></button>
        </a>
      </div>
      <div class='col-12 col-lg-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          LANGUAGES
        </div>
        <div class='ReadableText'>
          <span class="black">Italian</span><br>
          First language<br>
          <br>
          <span class="black">English</span><br>
          B2 IELTS Certificate (2018)<br>
        </div>
        <div class='EyecatchingTitle'>
          EDUCATION
        </div>
        <div class='ReadableText'>
          <span class="black">2021 - On going</span><br>
          Master Degree in Communication<br>
          Design at Politecnico di Milano<br>
          <br>
          <span class="black">2018 - 2021</span><br>
          Bachelor Degree in Communication<br>
          Design at Politecnico di Milano<br>
          <br>
          <span class="black">2013 - 2018</span><br>
          Artistic High School at Fondazione<br>
          Sacro Cuore, Milano<br>
        </div>
      </div>
      <div class='col-12 col-lg-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          SOFTWARE
        </div>
        <div class='ReadableText'>
          <span class="black">Suite Adobe CC</span><br>
          After Effects, Illustrator, Photoshop, Premiere Pro,
          Lightroom, InDesign, Audition, Adobe XD<br>
          <br>
          <span class="black">Suite</span><br>
          Excel, PowerPoint, Word<br>
          <br>
          <span class="black">Others</span><br>
          Figma, Keynote, Pages<br>
          <br>
          <span class="black">Coding</span><br>
          HTML, CSS, Bootstrap, Nuxt3, Vue<br>
        </div>
      </div>

    </div>
    </div>

    <LayoutFooter />

  </div>
</template>

<script>

export default {
  name: 'IndexPage',

}

</script>

<style>
.container-fluid {width:100%;max-width:none ;padding-left:0;padding-right:0}
</style>
