<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline">
        <span>NiceDrive</span>
        <span class="font-weight-light ml-3">Driver UI</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <span class="mr-2">IDF</span>
    </v-toolbar>

    <v-content>
      <DriverForm/>
    </v-content>
  </v-app>
</template>

<script>
import DriverForm from './components/DriverForm.vue'

export default {
  name: 'App',
  components: {
    DriverForm
  },
  data () {
    return {
      //
    }
  }
}
</script>