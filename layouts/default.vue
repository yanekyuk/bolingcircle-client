<template>
  <v-app>
    <v-content>
      <v-container class="main-container">
        <v-layout row wrap class="main-container-layout">
          <v-flex md4 offset-md1 class="left-block hidden-xs-only">
            <div class="left-block-info">
              <h2>Boğaziçi University</h2>
              <h1>Linguistics Circle</h1>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quibusdam eveniet earum, non eum rerum, voluptatibus vitae libero quasi consectetur adipisci optio totam fugit commodi suscipit quas ut cum, soluta aliquid.</p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias id maiores amet facilis reprehenderit dolor voluptas, doloremque nemo officia? Ipsam ut non est optio nemo voluptatibus consectetur voluptatum ullam commodi.</p>
              <img style="margin-left:-5px" src="../assets/logo.png" alt="">
            </div>
          </v-flex>
          <v-flex md5 offset-md1 class="right-block">
            <nuxt class="right-block-info" />
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
    <!-- <v-footer
      :fixed="fixed"
      app
    >
      <span>&copy; 2019</span>
    </v-footer> -->
  </v-app>
</template>

<script>
// import logo from '~/components/Logo.vue'

export default {
  name: 'Main'
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Fira+Sans:300,300&subset=latin-ext');

.application {
  font-family: 'Fira Sans', sans-serif;
  font-weight: 300;
  text-align: justify;
}

.main-container {
  position: relative;
  &-layout {
    position: fixed;
    top: 30px;
    bottom: 30px;
  }
}

.left-block {
  position: relative;
  display: flex;
  align-items: center;
  justify-content: center;
  &-info {
    &-logo {
      height: 100px;
    }
    h1 {
      margin-bottom: 10px;
    }
  }
}

.right-block {
  max-height: 100%;
}
</style>
