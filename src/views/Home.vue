<template>

  <v-container>

    <Main/>

    <Introducing/>

    <Ecosystem/>

    <Business/>

    <Team/>

    <Roadmap/>

  </v-container>

</template>

<script>

import Main from "@/components/partials/Main";
import Introducing from "@/components/partials/Introducing";
import Ecosystem from "@/components/partials/Ecosystem";
import Business from "@/components/partials/Business";
import Team from "@/components/partials/Team";
import Roadmap from "@/components/partials/Roadmap";

export default {
  name: 'Home',
  components: {
    Main,
    Introducing,
    Ecosystem,
    Business,
    Team,
    Roadmap
  },
  data: () => ({
    drawer: false,
    group: null,
  }),
}
</script>
