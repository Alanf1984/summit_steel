<template>
  <section id="intro" class="py-16">
    <v-container>
      <v-responsive class="max-auto mx-auto text-center" max-width="600">
        <v-col color="primary" size="70" class="mb-8">
          <v-img max-height="600" src="art.jpg" lazy-src="art.jpg"> </v-img>
        </v-col>

        <h2 class="text-h4 text-md-h3 text-center font-weight-black mb-7">
          The Perfect Project for your business
        </h2>
        <p class="title font-weight-light">
          A tailored solution for your business needs. Our expert team is ready
          to create a customized project that aligns seamlessly with your goals
          and objectives. See our differentials.
        </p>
      </v-responsive>

      <v-row class="pt-12">
        <v-col v-for="card in cards" :key="card.title" cols="12" md="4">
          <v-row no-gutters>
            <v-col :cols="card.callout ? 9 : 12">
              <div class="pr-2">
                <div class="text--disabled" v-text="card.subtitle"></div>
                <h4
                  class="text-uppercase mt-1 mb-4"
                  style="letter-spacing: 0.15em"
                  v-text="card.title"
                ></h4>
                <p v-text="card.text"></p>
              </div>
            </v-col>
            <v-col v-if="card.callout" cols="2">
              <span class="text-h3 grey--text font-weight-bold pr-8">{{
                card.callout
              }}</span>
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          title: 'Project Development and Planning',
          subtitle: 'Project',
          text: "One of Summit Steel's great differentials is the use of innovative solutions in projects, with its own highly qualified engineering team, working with the most modern project software on the market, proposing solutions adapted to the needs of each client. . Summit Steel operates with the entire constructive chain integrated in a collaborative and feedback-based manner throughout the entire process, always putting the customer at the center.",
          callout: '01',
        },
        {
          title: 'Own Manufacture',
          subtitle: 'Manufacturing',
          text: 'Summit Steel has one of the most modern industrial complexes in the market for the production of metallic structures, carrying several lines of profiles, welded and laminated profiles, tiles, paint, accessories, among others, thus being the most complete company in terms of solutions.',
          callout: '02',
        },
        {
          title: 'Practicality and Speed',
          subtitle: 'Assembly ',
          text: 'Summit Steel trains and qualifies its employees to learn about the different stages of the production process. From the beginning of engineering activities, the process is monitored by the Construction Manager, from project detailing to final assembly. Through this integrated management, it is possible to structure the detailed work schedule, aligning the stages of assembly of the structures.',
          callout: '03',
        },
      ],
    }
  },
}
</script>
