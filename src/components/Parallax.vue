<template>
  <div id="app">
    <v-app id="inspire">
      <section>
        <v-parallax
          dark
          style="min-height: 160vh;"
          src="https://wallpaperaccess.com/full/3521161.jpg"
        >
          <v-layout
            white--text
            align-center
            column
            justify-center
            style="margin-top: 8.5em"
          >
            <h3 class="display-3 ma-2 text-xs-center">Vuetify.js</h3>
            <h4 class="subheading">Parallax</h4>
            <v-flex row wrap text-xs-center>
              <v-btn dark large color="blue lighten-2" class="mt-4 elevation-0"
                >Parallax</v-btn
              >
            </v-flex>
          </v-layout>
        </v-parallax>
      </section>
    </v-app>
  </div>
</template>

<script>
export default {
  name: "PArallax",
};
</script>
<style scoped>
.homepage-toolbar {
  background: rgba(222, 222, 222, 0.4) !important;
  background: transparent !important;
  -webkit-box-shadow: none !important;
  box-shadow: none !important;
}
</style>