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
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.PreviewPretest'/>
    </b-col>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.LessicoVintage'/>
    </b-col>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.Persona'/>
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
          thumbnail: require('~/assets/Disruptive_thumbnail.png'),
          bio: 'A digital first exhibition born in 2020 portraying Sergio Marchionne life at Fiat',
          class: 'bgcol2',
          to: "about"
        },
        AdOk: {
          title: 'AdOk: the future is handcrafted',
          thumbnail: require('~/assets/AdOk_thumbnail.png'),
          bio: 'An interaction design project with the aim of revitalising Italian craftsmanship',
          class: 'bgcol1',
          to: "about"
        },
        PaoloVI: {
          title: 'Middle School Paolo VI',
          thumbnail: require('~/assets/PaoloVI_thumbnail.png'),
          bio: 'An elaborate communication project for a school that includes renewed brand identity and website',
          class: 'bgcol3',
          to: "about"
        },
        PreviewPretest: {
          title: 'Preview & Pretest',
          thumbnail: require('~/assets/PreviewPretest_thumbnail.png'),
          bio: 'A series of events promoted by students to help future designers and architects in their university pathway at Polimi',
          class: 'bgcol4',
          to: "about"
        },
        LessicoVintage: {
          title: 'Lessico Vintage',
          thumbnail: require('~/assets/LessicoVintage_thumbnail.png'),
          bio: 'A social media influencing project on vintage shops and events in the city of Milan',
          class: 'bgcol5',
          to: "about"
        },
        Persona: {
          title: 'Persona',
          thumbnail: require('~/assets/Persona_thumbnail.png'),
          bio: 'A speculative narration on the topic of the mask',
          class: 'bgcol6',
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

.bgcol1 {
  --color-secondary: #FFFBED;
}

.bgcol2 {
  --color-secondary: #458FDA;
}

.bgcol3 {
  --color-secondary: #DDDDDD;
}

.bgcol4 {
  --color-secondary: #DDC7FF;
}

.bgcol5 {
  --color-secondary: #FAFAFA;
}

</style>
