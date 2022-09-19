<template>
  <div class="footer-area pb-8">
    <v-container>
      <v-row>
        <v-col cols="12" md="3">
          <a href="">
            <img src="../assets/images/logo.png" alt="" class="header-logo">
          </a>
          <div class="social-links mt-4">
            <a href="#">
              <img src="../assets/images/linkedin.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/images/pngwing 1.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/images/image 2.png" alt="">
            </a>
            <a href="#">
              <img src="../assets/images/image 3.png" alt="">
            </a>
          </div>
        </v-col>
        <v-col cols="12" md="3" class="footer-menu">
          <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#business">Business model</a></li>
            <li><a href="#team">Team</a></li>
            <li><a href="#roadmap">Roadmap</a></li>
          </ul>
        </v-col>
        <v-col cols="12" md="3" class="footer-menu">
          <ul>
            <li><a href="#">Whitepaper</a></li>
            <li><a href="#">Pitchdeck</a></li>
            <li><a href="#">Go to app</a></li>
          </ul>
        </v-col>
        <v-col cols="12" md="3" class="footer-contacts">
          <h4 class="mb-4">Keep in touch</h4>
          <p>
            Phone:
            <a href="tel:+3487841378">+3487841378</a>
          </p>
          <p>
            Mail:
            <a href="mailto:nfitspace@gmail.com">nfitspace@gmail.com</a>
          </p>
        </v-col>
      </v-row>
    </v-container>
  </div>

</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>

</style>