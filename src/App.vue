<template>
  <v-app>
    <v-app-bar app color="white--text font-weight-light" dark>
      <a href="/home" class="header-info">
        <div class="d-flex align-center">
          <v-img
            alt="Logo"
            class="shrink mr-2"
            contain
            src="./assets/logo.png"
            transition="scale-transition"
            width="40"
          />

          <h1 id="logo-name">Notes</h1>
        </div>
      </a>
    </v-app-bar>

    <v-main>
      <router-view />
    </v-main>

    <v-footer padless color="yellow darken-2 white--text">
      <v-col class="text-center" cols="12">
        {{ new Date().getFullYear() }} — <strong>&copy; Google Notes</strong>
      </v-col>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Dongle:wght@300&display=swap");

.application,
.v-application {
  font-family: "Dongle", Arial, sans-serif;

  .header-info {
    color: #ffffff;
    text-decoration: none;

    h1 {
      font-weight: lighter;
    }
  }
}
</style>
