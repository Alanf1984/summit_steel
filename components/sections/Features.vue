<template>
  <section class="primary darken-1 white--text py-16">
    <v-container>
      <v-row>
        <v-col class="text-center">
          <h2 class="text-h4 text-md-h3 text-center font-weight-black">
            Build your dream with the Summit Steel
          </h2>
          <div
            class="text-h5 text-md-h4 text-center font-weight-black py-3 mb-10"
          >
            Our Competitive Edge
          </div>
        </v-col>
      </v-row>
      <v-row>
        <v-col
          v-for="(card, index) in cards"
          :key="index"
          cols="12"
          sm="4"
          class="text-center"
        >
          <v-avatar size="128" class="mb-7">
            <img
              :src="`/team/${card.avatar}`"
              alt="John"
              width="128"
              height="128"
            />
          </v-avatar>
          <div class="title text-uppercase mt-1 mb-4" v-text="card.title"></div>
          <p v-text="card.text"></p>
          <v-row no-gutters>
            <v-col cols="12"></v-col>
          </v-row>
        </v-col>
      </v-row>
      <v-row no-gutters>
        <v-btn
          x-large
          rounded
          color="white primary--text mx-auto mt-10 px-16"
          href="/services"
        >
          <v-icon dark left>mdi-check-bold</v-icon> Our services
        </v-btn>
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
          title: 'Project and Design',
          subtitle: 'Best Productivity',
          text: 'Unleash Your Vision with Stunning Precision! Our innovative team combines cutting-edge technology and creative expertise to bring your ideas to life. Experience the power of 3D visualization and meticulous design that captures every detail. With our advanced software and skilled professionals, we transform concepts into immersive virtual representations. From concept to reality, we ensure accuracy and efficiency in every step. Trust us to turn your dreams into awe-inspiring reality. Choose Project and Design for unrivaled excellence in architectural innovation!',
          avatar: 'person-41.jpg',
        },
        {
          title: 'Construction and Execution ',
          subtitle: 'Special Offers',
          text: 'Building Dreams with Excellence! Our expert team specializes in seamless construction and flawless execution. With precision planning and meticulous attention to detail, we bring your vision to life. Experience efficiency and professionalism at its best with our state-of-the-art technology and skilled craftsmen. From start to finish, we ensure timely completion and top-notch quality. Trust us to handle your project with expertise and deliver remarkable results. Choose Construction and Execution for a building experience beyond compare!',
          avatar: 'person-51.jpg',
        },
        {
          title: 'Fast build',
          subtitle: 'Income Flow',
          text: ' Turn your project into reality quickly and efficiently! Our highly skilled team and cutting-edge technology ensure fast and high-quality execution. With precise planning and efficient coordination, we deliver your dream built in record time. Maximize productivity with our clear communication and effective collaboration. Safety comes first, complying with all regulations. Choose the excellence of fast construction for impressive results!',
          avatar: 'person-61.jpg',
        },
      ],
    }
  },
}
</script>
