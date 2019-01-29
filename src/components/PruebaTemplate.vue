<template>
  <v-app id="inspire">

    <v-container
      grid-list-md
      text-xs-left
    >
      <v-layout
        row
        wrap
      >

        <v-flex xs12>
          <v-card
            dark
            color="primary"
          >
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>visibility</v-icon>
              </v-btn>Titulo
            </v-card-text>
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>visibility</v-icon>
              </v-btn>Codigo
            </v-card-text>
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>visibility</v-icon>
              </v-btn>Apellido
            </v-card-text>
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>visibility</v-icon>
              </v-btn>Nombre
            </v-card-text>
          </v-card>
        </v-flex>

        <v-flex xs6>
          <v-card
            dark
            color="secondary"
          >
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>
                  calendar_today</v-icon>
              </v-btn>Fecha
            </v-card-text>
          </v-card>
        </v-flex>
        <v-flex xs6>
          <v-card
            dark
            color="secondary"
          >
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>monetization_on</v-icon>
              </v-btn>Monto
            </v-card-text>
          </v-card>
        </v-flex>
        <v-flex xs6>
          <v-card
            dark
            color="secondary"
          >
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>
                  calendar_today</v-icon>
              </v-btn>Fecha
            </v-card-text>
          </v-card>
        </v-flex>
        <v-flex xs6>
          <v-card
            dark
            color="secondary"
          >
            <v-card-text class="px-0">
              <v-btn icon>
                <v-icon>monetization_on</v-icon>
              </v-btn>Monto
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>

  </v-app>
</template>

<script>
export default {
  data: () => ({
    drawer: null
  }),
  props: {
    source: String
  }
};
</script>