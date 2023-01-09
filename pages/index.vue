<template>
  <div class='container-fluid'>

    <LayoutNavbarHome />

    <div class='row row-herosection align-items-center mx-3'>
      <div class="col-12">
        <div class='BigAFTitle'>HI, I’M DAVIDE<br>
          NOT MUCH TO SAY, EXCEPT<br>THAT I’M INTO COMMUNICATION DESIGN SOMEHOW
        </div>
      </div>
    </div>

    <div class='row-progetti'>
      <div class='row mx-3 pt-5 justify-content-between align-items-center'>
        <div class='col-6'>
          <div class='KindaBigTitle'>
            TAKE A LOOK AT<br>MY PROJECTS
          </div>
        </div>
          <div class='col-6'>
            <div class='ReadableTextDefault'>
              Between 2018 and 2023 I had been enrolled<br>
              in Communication Design at Politecnico di Milano.<br>
              In these years i have explored many fields of this<br>
              discipline, with projects inside and outside<br>
              of the courses, with the precise aim of finding<br>
              my place in the world, at least one to work in.<br>
            </div>
          </div>
      </div>
      <LayoutProjects />
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
