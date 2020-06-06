<template>
  <div class="login">
    <header-frontend />

    <v-content>
      <v-container fluid fill-height>
        <v-layout align-center justify-center>
          <v-flex xs12 md8 lg6>
            <v-card class="ma-5 pa-5" shaped>

              <v-card-title>
                <span class="text-center">Login</span>
              </v-card-title>

              <v-card-text>
                <v-text-field label="Email" filled autofocus />

                <v-text-field label="Senha" filled type="password" />
                <v-row>
                <v-btn text small>Esquece a senha?</v-btn>
                </v-row>
              </v-card-text>

              <v-card-actions>
                <v-spacer />
                <v-btn>Entrar</v-btn>
              </v-card-actions>

            </v-card>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>

    <footer-main />
  </div>
</template>

<script>
import FooterMain from '../components/Frontend/Footer'

export default {
  components: {
    FooterMain
  }
}
</script>

<style>

</style>
