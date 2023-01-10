<template>
  <div>
    <b-row ref="projectsContainer" class="">
      <b-col  cols="12" md="6" lg="4">
        <LayoutCardNew v-bind='projects.Disruptive'/>
      </b-col>
    </b-row>
  </div>
</template>

<script>
export default {
  name: "ProjectsD",
  data() {
    return {
      projects: {
        Disruptive: {
          title: 'Disruptive: the challenge of rebuilding',
          thumbnail: '~/assets/Disruptive_cover.png',
          bio: 'A digital first exhibition born in 2020 portraying Sergio Marchionne life at Fiat',
          to: "about"
        },
      },
    }
  },
}
</script>


<style>

h6{
  --color-secondary: white;
}
@media (max-width: 768px) {
  .btn {
    padding-left: 9px;
    padding-right: 9px;
  }
  p{
    font-size: 14px;
  }
}
</style>
