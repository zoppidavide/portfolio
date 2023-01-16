<template>
  <div class='container-fluid'>

    <LayoutNavbarHome />

    <LayoutNicetomeetyou />

<!--    <div class='row mx-1 mx-lg-3 row-herosection align-items-end d-flex justify-content-center'>
      <div class="col-12">
        <div class='BigAFTitle'>
          Hi, I’m Davide, 23 yo italian communication<br>
          and experience designer, currently enrolled<br>
          in Communication Master Degree at Polimi<br>
        </div>
      </div>
    </div>-->

    <div class='row mx-1 mx-lg-3 mt-3 row-herosection2 align-items-start d-flex justify-content-center'>
      <a href="#mieiprogetti"> <b-button class="huge mt-3 py-2 align-items-center justify-content-between"><span class="icon-arrow"></span>SELECTED WORKS<span></span></b-button> </a>
    </div>

    <div id="mieiprogetti" class='row-progetti'>
      <div class='row mx-1 mx-lg-3 pt-5 justify-content-between align-items-center'>
        <div class='col-lg-4 col-sm-12 mt-2 mt-lg-5'>
          <div class='KindaBigTitle'>
            TAKE A LOOK AT
            MY PROJECTS
          </div>
        </div>
          <div class='col-lg-5 col-sm-12 mt-3 mt-lg-5'>
            <div class='ReadableTextDefault'>
              Between 2018 and 2023 I had been enrolled
              in Communication Design at Politecnico di Milano.
              In these years i have explored many fields of this
              discipline, with projects inside and outside
              of the courses, with the precise aim of finding
              my place in the world, at least one to work in.
            </div>
          </div>
      </div>
<!--      <LayoutProjects />-->
      <LayoutGridNew />
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
