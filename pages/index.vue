<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <v-card>
        <logo />
        <v-card-title class="headline">
          VDojo - nauka STEM online dla ludzi w każdym wieku!
        </v-card-title>
        <v-card-text>
          <p>Hej! Jesteśmy grupą ludzi z krakowskiego oddziału
            <a
              href="https://coderdojo.org.pl"
              target="_blank"
            >
              CoderDojo Polska
            </a>,
            fundacji non-profit uczącej dzieci i młodzież programowania i innych nauk z zakresu STEM. </p>
          <p>
            Przez obecną sytuację z koronawirusem, zmuszeni zostaliśmy do wstrzymania zajęć z naszymi ninja.
            Nasza pasja do programowania nie wygasła jednak, i wpadliśmy na pomysł stworzenia portalu z zadaniami
            z różnych dziedzin ścisłych.
          </p>
          <p>
            Jeżeli macie pytania, zapraszamy na nasz oficjalny
            <a
              href="https://chat.vuetifyjs.com/"
              target="_blank"
              title="chat"
            >
              serwer Discord
            </a>.
          </p>
          <p>Kod zarówno front-end'u jak i back-end'u jest udostępniony na licencji Apache License 2.0 na naszym
            <a
              href="https://github.com/vdojo"
              target="_blank"
            >
              GitHub'ie
            </a>.
          </p>
          <hr class="my-3">
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
