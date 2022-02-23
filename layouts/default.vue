<template>
  <v-app dark>
    <v-app-bar
      :clipped-left="clipped"
      fixed
      app
    >
      
    </v-app-bar>
    <v-main>
      <v-container>
        <nuxt />
      </v-container>
    </v-main>


  </v-app>
</template>

<script>
import index from '../pages/index.vue'
export default {
  components: { index },
  name: 'DefaultLayout'
}
</script>
