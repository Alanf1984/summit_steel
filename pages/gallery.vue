<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <v-container class="py-16">
          <v-row>
            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`pexels-andrea-piacquadio-3830745.jpg`"
                :lazy-src="`pexels-andrea-piacquadio-3830745.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`bathrust.jpg`"
                :lazy-src="`bathrust.jpg`"
                aspect-ratio="2"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`brita.jpg`"
                :lazy-src="`brita.jpg`"
                aspect-ratio="3"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`chuva.jpg`"
                :lazy-src="`chuva.jpg`"
                aspect-ratio="4"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`const.jpg`"
                :lazy-src="`const.jpg`"
                aspect-ratio="5"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`downest.jpg`"
                :lazy-src="`downest.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`escada.jpg`"
                :lazy-src="`escada.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`estr_pick.jpg`"
                :lazy-src="`estr_pick.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`estrutura.jpg`"
                :lazy-src="`estrutura.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`fase1.jpg`"
                :lazy-src="`fase1.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`gerador.jpg`"
                :lazy-src="`gerador.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>

            <v-col :key="n" class="d-flex child-flex" cols="4" xl="3">
              <v-img
                :src="`mezanino.jpg`"
                :lazy-src="`mezanino.jpg`"
                aspect-ratio="1"
                class="grey lighten-2 rounded-lg"
              >
              </v-img>
            </v-col>
          </v-row>
        </v-container>
      </v-col>
    </v-row>
  </section>
</template>

<script>
export default {
  data() {
    return {
      heroAlt: [
        {
          src: 'pexels-andrea-piacquadio-3830745.jpg',
          heading: ' Gallery ',
        },
      ],
    }
  },
  head() {
    return {
      title: 'Gallery',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'Infographic hypotheses influencer user experience Long madel ture gen-z paradigm shift client partner network product seilans solve management influencer analytics leverage virality. incubator seed round massmarket. buyer agile development growth hacking business-to-consumer ecosystem',
        },
      ],
    }
  },
}
</script>
