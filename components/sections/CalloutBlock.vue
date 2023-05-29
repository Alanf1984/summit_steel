<template>
  <section
    :class="
      $vuetify.theme.dark
        ? 'grey darken-4 primary--text text--lighten-1'
        : 'grey lighten-4 primary--text'
    "
    class="primary--text py-16"
  >
    <v-container>
      <v-row>
        <v-col>
          <v-row no-gutters>
            <v-col cols="12" sm="7" class="text-center">
              <h2
                class="text-h4 text-md-h3 text-left font-weight-black text-capitalize mb-4"
              >
                Consult us for your project
              </h2>

              <p class="text-left">
                We're excited to hear from you!<br />
                Contact us to discuss your project, ask questions, or get more
                information. We're ready to assist and provide customized
                solutions to meet your needs.
              </p>
            </v-col>
            <v-col align-self="center" cols="12" sm="5" class="text-center">
              <v-btn x-large color="primary" rounded href="/contact"
                >Contact us</v-btn
              >
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </section>
</template>
