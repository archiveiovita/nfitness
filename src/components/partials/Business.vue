<template>
  <v-row class="business-model-area" id="business">
    <v-col cols="12" md="12" class="text-center mb-8">
      <h2 class="mb-4">NFiTNESS Business Model</h2>
      <p>The marketplace allows users to create chains of NFTs, formed by initial workout/meal plan upgraded by the
        history of its usage. The more experience of usage a workout/meal plan users attach, the more valuable and
        expensive it becomes and more royalty gets the trainer and previous owners from each transaction. Thus,
        everybody in the chain is motivated to make the initial NFT better by adding more value to it through personal
        experience.</p>
    </v-col>
    <v-col cols="12" md="12" class="mb-8 item-1">
      <div class="business-model-item">
        <img src="@/assets/images/NFT sales 1 1.png" alt="" height="250px">
      </div>
    </v-col>
    <v-col cols="12" md="12" class="mb-8 item-2">
      <div class="business-model-item">
        <img src="@/assets/images/NFT sales 2 1.png" alt="" height="235px">
      </div>
    </v-col>
    <v-col cols="12" md="12" class="mb-8 item-3">
      <div class="business-model-item">
        <img src="@/assets/images/NFT sales 3.png" alt="" height="288px">
      </div>
    </v-col>
    <v-col cols="12" md="12" class="text-center mb-8">
      <button class="project-button" @click="redirectPitch">Pitch deck</button>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "Business",
  methods: {
    redirectPitch() {
      window.open("https://www.canva.com/design/DAFLvXYt2NI/O4FFpZ-jwpmDjhESgB6k-g/view?utm_content=DAFLvXYt2NI&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink");
    }
  }
}
</script>

<style scoped>

</style>