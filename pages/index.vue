<template>
  <div class='container-fluid'>

    <LayoutNavbarHome />

    <div class='row mx-1 row-herosection align-items-center'>
      <div class="col-12">
        <div class='BigAFTitle'>HI, I’M DAVIDE<br>
          NOT MUCH TO SAY, EXCEPT THAT I’M INTO COMMUNICATION DESIGN SOMEHOW
        </div>
      </div>
    </div>

    <div class='row-progetti'>
      <div class='row mx-1 mx-lg-3 pt-5 justify-content-between align-items-center'>
        <div class='col-lg-4 col-sm-12'>
          <div class='KindaBigTitle'>
            TAKE A LOOK AT
            MY PROJECTS
          </div>
        </div>
          <div class='col-lg-5 col-sm-12'>
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
