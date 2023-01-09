<template>
  <div class='container-fluid'>

    <LayoutNavbarAbout />

    <div class='row row-herosection align-items-center mx-3'>
      <div class="col-8">
        <div class='testone'>Mi chiamo Gennaro Esposito, sono figlio di un padre camorrista e una madre pasticcera, da loro ho compreso l’importanza dell’intraprendenza. Il mio approccio al design è di tipo scontroso.<br>
          <br>Negli anni dei miei studi presso l’università della strada Federico II a Napoli mi sono appassionato al design degli eventi, in particolare matrimoni, cresime e battesimi napoletani, ma anche funerali della famiglia Casamonica. Quando non sono con la mia ragazza Annunziata e non sto facendo estorsioni o scambi di persona penso al design. Jamm’è Ja!
        </div>
      </div>
      <div class="col-4">
        <LayoutAboutPhoto />
      </div>
    </div>

    <div class='container-fluid classprova'>
      <div class='row row-info mx-3'>
      <div class='col-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          EXPERIENCES
        </div>
        <div class='ReadableText'>
          March 2022 - October 2022<br>
          <span class="bold">Motion and graphic design intern<br>
          at Politecnico di Milano</span><br>
          <br>
          September 2021 - October 2022<br>
          <span class="bold">UX Design and branding<br>
          at Paolo VI secondary school</span><br>
          <br>
          June 2020 - December 2020<br>
          <span class="bold">Motion designer and social media<br>
          content creation at Storytel</span><br>
          <br>
          September 2019 - October 2020<br>
          <span class="bold">Motion designer for Ziio Jewels</span><br>
        </div>
        <div class='EyecatchingTitle'>
          DOWNLOAD CV
        </div>
        <a href="https://getbootstrap.com/docs/4.3/layout/grid/"><img src = "~/assets/arrow.svg" alt="GoTo"/></a>
      </div>
      <div class='col-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          LANGUAGES
        </div>
        <div class='ReadableText'>
          Italian<br>
          <span class="bold">First language</span><br>
          <br>
          English<br>
          <span class="bold">B2 IELTS Certificate (2018)</span><br>
        </div>
        <div class='EyecatchingTitle'>
          EDUCATION
        </div>
        <div class='ReadableText'>
          2021 - On going<br>
          <span class="bold">Master Degree in Communication<br>
          Design at Politecnico di Milano</span><br>
          <br>
          2018 - 2021<br>
          <span class="bold">Bachelor Degree in Communication<br>
          Design at Politecnico di Milano</span><br>
          <br>
          2013 - 2018<br>
          <span class="bold">Artistic High School at Fondazione<br>
          Sacro Cuore, Milano</span><br>
        </div>
      </div>
      <div class='col-4 colonna-cv'>
        <div class='EyecatchingTitle'>
          SOFTWARE
        </div>
        <div class='ReadableText'>
          Suite Adobe CC<br>
          <span class="bold">After Effects, Illustrator, Photoshop, Premiere Pro,
          Lightroom, InDesign, Audition, Adobe XD</span><br>
          <br>
          Suite<br>
          <span class="bold">Excel, PowerPoint, Word</span><br>
          <br>
          Others<br>
          <span class="bold">Figma, Keynote, Pages</span><br>
          <br>
          Coding<br>
          <span class="bold">HTML, CSS, Bootstrap, Nuxt3, Vue</span><br>
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
