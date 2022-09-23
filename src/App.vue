<template>
  <v-app>
    <v-app-bar><v-app-bar-title>VITE</v-app-bar-title></v-app-bar>
    <v-main>
      <v-container>
      <v-card>
        <v-card-text color="secondary-text">fsdfsdf</v-card-text>
        <v-btn color="secondary">test</v-btn>
      </v-card>
      <HelloWorld/>
      </v-container>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'

export default defineComponent({
  name: 'App',

  components: {
    HelloWorld,
  },

  data () {
    return {
      //
    }
  },
})
</script>
