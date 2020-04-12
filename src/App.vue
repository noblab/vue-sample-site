<template>
  <v-app>
    <v-app-bar
      app
      color="teal lighten-1"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="study"
          class="shrink mr-2"
          contain
          src="./assets/study.svg"
          transition="scale-transition"
          width="40"
        />
        <v-btn
        text
        href="#"
        >Nano Portofolio</v-btn>

      </div>

      <v-spacer></v-spacer>
      <v-btn
      text
      href="#timeline"
      >About</v-btn>
      <v-btn text href="https://alis.to/users/cryptoMedNano">Columns</v-btn>
      <v-btn text href="https://twitter.com/cryptomed_nano">Twitter</v-btn>
      <v-btn text href="https://www.linkedin.com/in/%E6%98%87-%E4%B8%AD%E5%8E%9F-901773197/">LinkedIn</v-btn>
      <v-btn text href="facebook.com/nakahranoboru">Facebook</v-btn>
    </v-app-bar>

    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
