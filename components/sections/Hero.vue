<template>
  <section id="hero">
    <v-carousel
      height="calc(100vh - 64px)"
      dark
      cycle
      show-arrows-on-hover
      draggable="true"
      hide-delimiter-background
    >
      <v-carousel-item
        v-for="(carousel, carindex) in carouselsData"
        :key="carindex"
        :src="carousel.src"
        class="gradient-fill"
      >
        <v-container fill-height>
          <div style="max-width: 600px">
            <div
              class="text-md-h2 mb-3 text-sm-h3 text-h5 font-weight-black white--text"
            >
              {{ carousel.heading.toUpperCase() }}
            </div>
            <p class="mb-5 white--text">{{ carousel.subHeading }}</p>
            <v-btn :x-large="$vuetify.breakpoint.smAndUp" class="my-3 primary"
              >Get Started</v-btn
            >
            <span class="mx-2 my-4"></span>
            <v-btn
              :x-large="$vuetify.breakpoint.smAndUp"
              text
              class="my-3"
              outlined
              dark
              ><v-icon left large color="primary">mdi-play</v-icon>Learn
              More</v-btn
            >
          </div>
        </v-container>
      </v-carousel-item>
    </v-carousel>
  </section>
</template>

<script>
export default {
  data() {
    return {
      carouselsData: [
        {
          src: 'fase1.jpg',
          heading: ' BUILD YOUR BUSINESS WITH US ',
          subHeading:
            'Summit Steel, a leader in the design, fabrication and installation of high-quality steel structures for the construction ',
        },
        {
          src: 'pexels-peter-olexa-4012966.jpg',
          heading: ' HIGHLY QUALIFIED PROFESSIONALS',
          subHeading:
            'Our experts have the experience and knowledge necessary to deliver high-quality steel construction projects.',
        },
        {
          src: 'pexels-thirdman-5961072.jpg',
          heading: 'Quality equipment',
          subHeading:
            'With our state-of-the-art equipment, we are able to execute construction tasks efficiently and with precision. From cutting and shaping steel components to assembling structures, our professionals utilize quality equipment that meets industry standards.',
        },
        {
          src: 'neve.jpg',
          heading: ' FAST AND CLEAN WORK',
          subHeading:
            'Com métodos de trabalho otimizados e uma abordagem focada na limpeza do local, garantimos que o projeto seja concluído de forma ágil e sem deixar resíduos indesejados. Nossos profissionais são treinados para executar suas tarefas com rapidez e precisão, sem comprometer a qualidade do trabalho. Conte conosco para um serviço confiável, rápido e limpo em construção em aço.',
        },
      ],
    }
  },
}
</script>

<style>
.gradient-fill .v-responsive__content {
  background: rgb(0, 0, 0);
  background: linear-gradient(
    to right,
    rgba(3, 12, 41, 0.75),
    rgba(5, 11, 31, 0.65)
  );
}
</style>
