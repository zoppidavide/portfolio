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
          thumbnail2: require('~/assets/disruptive_1.jpg'),
          description2: 'The challenge of rebuilding. A project hiding an other challenge, being able to rethink the way people can “visit” an exhibition in a pandemic period.',
          role2: 'Project concept, web development, mobile application UI, storytelling',
          team2: 'Federico Pozzi, Marco Pari, Andrea Silvano, Giovanni Clericetti, Alice Bocchio, Michele Bruno',
          to2: "https://disruptive.meetingrimini.org/",
          link2: 'Visit the website ↗︎',
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
