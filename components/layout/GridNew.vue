<template>
  <div class='row mx-1 mx-lg-3 pt-5'>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.AdOk'/>
    </b-col>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.Disruptive'/>
    </b-col>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.PaoloVI'/>
    </b-col>
    </div>
</template>

<script>
export default {
  name: "GridNew",
  data() {
    return {
      projects: {
        Disruptive: {
          title: 'Disruptive: the challenge of rebuilding',
          thumbnail: '~/assets/Disruptive_cover.png',
          bio: 'A digital first exhibition born in 2020 portraying Sergio Marchionne life at Fiat',
          to: "about"
        },
        AdOk: {
          title: 'AdOk: the future is handcrafted',
          thumbnail: '~/assets/AdOk_thumbnail.png',
          bio: 'An interaction design project with the aim of revitalising Italian craftsmanship',
          to: "about"
        },
        PaoloVI: {
          title: 'Middle School Paolo VI',
          thumbnail: '~/assets/PaoloVI_thumbnail.png',
          bio: 'An elaborate communication project for a school that includes renewed brand identity and website',
          to: "about"
        },
      },
    }
  },
}
</script>

<style>
.prova {
  padding-top: 30px;
}
</style>
