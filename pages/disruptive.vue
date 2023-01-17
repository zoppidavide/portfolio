<template>

  <div class='container-fluid'>

    <LayoutNavbarProjects />

    <LayoutHeroProg v-bind='intro.Disruptive'/>

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
          thumbnail2: require('~/assets/Disruptive_thumbnail.png'),
          description2: 'A digital first exhibition born in 2020 portraying Sergio Marchionne life at Fiat',
          tag1: 'bgcol2',
          tag2: 'bgcol2',
          tag3: 'bgcol2'
        }
      }
    }
  }
}
</script>

<style>

</style>
