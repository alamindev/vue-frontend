<template>
  <v-app> 
  <Header/>
    <v-main>
      <v-container fluid class="pa-0">
        <nuxt />
      </v-container>
    </v-main> 
  </v-app>
</template>

<script>
import Header from './header'
export default {
  components: {
    Header
  },
  data () {
    return {

    }
  }
}
</script>
  