<template>
  <v-row class="roadmap-area" id="roadmap">
    <v-col cols="12" class="text-center mb-8">
      <h2 class="mb-4">Roadmap</h2>
    </v-col>
    <div class="roadmap">
      <div class="roadmap-item roadmap-item1"></div>
      <div class="roadmap-item roadmap-item2"></div>
      <div class="roadmap-item roadmap-item3"></div>
      <div class="roadmap-item roadmap-item4"></div>
    </div>
    <div class="roadmap-list">
      <div class="roadmap-list-item">
        <h5>2022 - Q2</h5>
        <ul>
          <li>Online platform launched with a test content</li>
        </ul>
      </div>
      <div class="roadmap-list-item">
        <h5>2022 - Q3</h5>
        <ul>
          <li>Blockchain technology study, building team</li>
          <li>P2P fitness marketplace build</li>
        </ul>
      </div>
      <div class="roadmap-list-item">
        <h5>2022 - Q4</h5>
        <ul>
          <li>Train & Earn (pyramid concept)</li>
          <li>Chain of recursive NFTs module build</li>
          <li>NFT multipack functionality build</li>
        </ul>
      </div>
      <div class="roadmap-list-item">
        <h5>2022 - Q1</h5>
        <ul>
          <li>Launch (Mainnet)</li>
          <li>Community expansion, mediatization</li>
          <li>Preparation for fundraising, IDO, TGE, etc.</li>
        </ul>
      </div>
    </div>
    <v-col class="text-center mt-8 mb-8">
      <button class="project-button" @click="redirect">Whitepaper</button>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Roadmap",
  methods: {
    redirect() {
      window.open("https://docs.nfitness.space");
    }
  }
}
</script>

<style scoped>

</style>