<template>
  <div class='row mx-1 mx-lg-3 pt-3 pt-lg-5'>
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
      <LayoutCardNew v-bind='projects.MagModa'/>
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
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.ArmaniSilos'/>
    </b-col>
    <b-col cols="12" md="6" lg="4" class='prova'>
      <LayoutCardNew v-bind='projects.Negroni'/>
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
          to: "disruptive"
        },
        AdOk: {
          title: 'AdOk: the future is handcrafted',
          thumbnail: require('~/assets/AdOk_thumbnail.png'),
          bio: 'An interaction design project with the aim of revitalising Italian craftsmanship',
          class: 'bgcol1',
          to: "adok"
        },
        PaoloVI: {
          title: 'Middle School Paolo VI',
          thumbnail: require('~/assets/PaoloVI_thumbnail.png'),
          bio: 'An elaborate communication project for a school that includes renewed brand identity and website',
          class: 'bgcol3',
          to: "paolovi"
        },
        PreviewPretest: {
          title: 'Preview & Pretest',
          thumbnail: require('~/assets/PreviewPretest_thumbnail.png'),
          bio: 'A series of events promoted by students to help future designers and architects in their university pathway at Polimi',
          class: 'bgcol4',
          to: "previewpretest"
        },
        LessicoVintage: {
          title: 'Lessico Vintage',
          thumbnail: require('~/assets/LessicoVintage_thumbnail.png'),
          bio: 'A social media influencing project on vintage shops and events in the city of Milan',
          class: 'bgcol5',
          to: "lessicovintage"
        },
        Persona: {
          title: 'Persona',
          thumbnail: require('~/assets/Persona_thumbnail.png'),
          bio: 'A speculative narration about interpersonal relationship possible futures in our daily life',
          class: 'bgcol6',
          to: "persona"
        },
        MagModa: {
          title: 'Mag Moda: a SME digital transformation',
          thumbnail: require('~/assets/MagModa_thumbnail.png'),
          bio: 'Designing a digital go-to-market strategy to allow a B2B company to reach the target and start communicating',
          class: 'bgcol8',
          to: "magmoda"
        },
        ArmaniSilos: {
          title: 'Armani Silos',
          thumbnail: require('~/assets/ArmaniSilos_thumbnail.png'),
          bio: 'Harnessing the potential of design makes it possible to conceive accessible storytelling for those suffering from sensorial impairments',
          class: 'bgcol9',
          to: "armanisilos"
        },
        Negroni: {
          title: 'Negroni',
          thumbnail: require('~/assets/Negroni_thumbnail.png'),
          bio: 'A visual campaign to celebrate the 90th anniversary of the flagship product of a truly iconic made-in-Italy food company',
          class: 'bgcol7',
          to: "negroni"
        },
      },
    }
  },
}
</script>

<style>

@media screen and (min-width: 481px) {
  .prova {
    padding-top: 30px;
  }
}

@media screen and (max-width: 480px) {
  .prova {
    padding-top: 30px;
  }
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

.bgcol6 {
  --color-secondary: #ebedec;
}

.bgcol7 {
  --color-secondary: #c9c9c9;
}

.bgcol8 {
  --color-secondary: #F45733;
}

.bgcol9 {
  --color-secondary: #dddfe5;
}

</style>
