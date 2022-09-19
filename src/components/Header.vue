<template>
  <v-container fluid class="header">

    <v-app-bar color="white" elevation="0">
      <div class="menu__burger mobile-only" @click="drawer = true"><span>toggle</span></div>

      <v-spacer class="mobile-only"></v-spacer>

      <img src="../assets/images/logo.png" alt="" class="header-logo">

      <ul class="header-menu desktop-only">
        <li><a href="#about">About</a></li>
        <li><a href="#business">Business Model</a></li>
        <li><a href="#team">Team</a></li>
        <li><a href="#roadmap">Roadmap</a></li>
      </ul>

      <v-spacer class="desktop-only"></v-spacer>

      <ul class="header-menu desktop-only">
        <li><a href="#">Whitepaper</a></li>
        <li><a href="#">PitchDeck</a></li>
      </ul>

      <button class="project-button desktop-only">Go to App</button>

    </v-app-bar>

    <v-navigation-drawer
        v-model="drawer"
        absolute
        temporary
    >
      <v-list
          nav
          dense
      >
        <v-list-item-group
            v-model="group"
            active-class="deep-purple--text text--accent-4"
        >

          <img src="../assets/images/logo.png" alt="" class="header-logo">

          <v-list-item><a href="#about">About</a></v-list-item>
          <v-list-item><a href="#business">Business Model</a></v-list-item>
          <v-list-item><a href="#team">Team</a></v-list-item>
          <v-list-item><a href="#roadmap">Roadmap</a></v-list-item>

          <v-list-item><a href="#">Whitepaper</a></v-list-item>
          <v-list-item><a href="#">PitchDeck</a></v-list-item>

          <button class="project-button">Go to App</button>

        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </v-container>
</template>
<script>

import {mdiAccount} from "@mdi/js";

export default {
  name: 'Header',
  data: () => ({
    drawer: false,
    group: null,
    icons: {
      mdiAccount
    }
  }),

  watch: {
    group() {
      this.drawer = false
    },
  },
}
</script>
