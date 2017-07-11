<template>
    <v-layout row wrap>
        <v-flex xs12>
            <h2 class="text-xs-center">Vuelp</h2>
        </v-flex>
      <v-flex sm6>
          <v-text-field
            name="search-query"
            label="Find"
            id="search-query"
          ></v-text-field>
        </v-flex>
        <v-flex sm6>
            <v-text-field
              name="search-location"
              label="Location"
              id="search-location"
            ></v-text-field>
          </v-flex>
      </v-layout>
</template>
<script>
  export default {
    data () {
      return {
          'title': 'Store Locator'
      }
    }
  }
</script>
