<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline">
        <span>NiceDrive</span>
        <span class="font-weight-light ml-3">Manager UI</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <span class="mr-2">IDF</span>
    </v-toolbar>

    <v-content>
      <DataTable/>
    </v-content>
  </v-app>
</template>

<script>
import DataTable from './components/DataTable.vue'

export default {
  name: 'App',
  components: {
    DataTable
  },
  data () {
    return {
      //
    }
  }
}
</script>