<template>
  <section>
    <v-row no-gutters>
      <v-col cols="12">
        <SectionsHeroAlt :hero-alt="heroAlt" />
        <v-container>
          <v-row class="py-16">
            <v-col cols="12">
              <SectionsIntro />
              <h2
                class="text-h4 text-md-h3 text-center font-weight-black text-capitalize"
              >
                What we do?
              </h2>
              <h3
                class="text-h2 text-uppercase font-weight-black text-center my-8"
              >
                STEEL PROJECTS
              </h3>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Steel constructive solutions for horizontal constructions,
                multi-story, infrastructure works, process structures and pipe
                racks, and special projects. Design, manufacture and assembly.
              </h3>
            </v-col>
          </v-row>
        </v-container>

        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="mezanino4.jpg"
              lazy-src="mezanino4.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                INFRASTRUCTURE
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Summit Steel is a reference in heavy and special metallic
                structures, operating in the Infrastructure...
              </h3>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="12" md="6" align-self="center">
            <v-img max-height="800" src="fase1.jpg" lazy-src="fase1.jpg">
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                HORIZONTAL CONSTRUCTIONS
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Summit Steel is a reference in metallic structures in many
                segments, but one of the types of work...
              </h3>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img max-height="800" src="mezanino.jpg" lazy-src="mezanino.jpg">
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">MULTISTOREY</h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Summit Steel is a reference in metallic structures in several
                segments. Multi-story projects...
              </h3>
            </div>
          </v-col>
        </v-row>
        <v-row no-gutters>
          <v-col cols="12" md="6" align-self="center">
            <v-img max-height="800" src="tim.jpg" lazy-src="tim.jpg"> </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                SPECIAL PROJECTS
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Summit Steel has solutions in the design, manufacture and
                assembly of works that require special structures such as
                hangars and projects with differentiated architectural design..
              </h3>
            </div>
          </v-col>
        </v-row>

        <h3 class="text-h2 text-uppercase font-weight-black text-center my-8">
          TECHNICAL SERVICES
        </h3>
        <h3 class="text-h5 text-uppercase font-weight-thin text-center my-8">
          Learn more about our technical services. Corrective maintenance,
          preventive maintenance, retrofit and intelligent solutions for steel
          projects and works with metallic structures.
        </h3>

        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img
              max-height="800"
              src="mezanino5.jpg"
              lazy-src="mezanino5.jpg"
            >
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                CORRECTIVE MAINTENANCE
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Through effective methodologies, it promotes the recovery of
                products and systems that have been damaged or misused,
                providing better performance and safety for buildings.
              </h3>
            </div>
          </v-col>
        </v-row>

        <v-row no-gutters>
          <v-col cols="12" md="6" align-self="center">
            <v-img max-height="800" src="manut.jpeg" lazy-src="manut.jpeg">
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">
                PREVENTIVE MAINTENANCE
              </h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                The preventive maintenance service performs inspections and
                repairs on a scheduled basis, extending the durability of
                assets, reducing risks and costs with possible emergencies.
              </h3>
            </div>
          </v-col>
        </v-row>

        <v-row no-gutters class="flex-row-reverse">
          <v-col cols="12" md="6" align-self="center">
            <v-img max-height="800" src="anexo.jpg" lazy-src="anexo.jpg">
            </v-img>
          </v-col>
          <v-col cols="12" md="6" align-self="center">
            <div class="pa-lg-16 pa-md-10 px-4 py-16">
              <h2 class="text-h3 text-center font-weight-black">Retrofit</h2>
              <h3
                class="text-h5 text-uppercase font-weight-thin text-center my-8"
              >
                Summit Steel Serviços Técnicos, through Retrofit, manages to
                adapt its building to the most modern standards in the market
                and to new regulatory norms, increasing the use of the area and
                optimizing its performance.
              </h3>
            </div>
          </v-col>
        </v-row>
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
          src: 'mezanino.jpg',
          heading: ' Services',
        },
      ],
    }
  },
  head() {
    return {
      title: 'About Us',
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
