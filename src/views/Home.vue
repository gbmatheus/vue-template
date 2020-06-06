<template>
  <div class="home">
    <header-frontend />

    <v-content>
      <v-container>
        Inicio
      </v-container>
    </v-content>

    <FooterMain />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import FooterMain from '../components/Frontend/Footer.vue'

export default {
  components: {
    FooterMain
  }
}

</script>
