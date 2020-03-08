<template>
  <v-app>
    <HeaderBar></HeaderBar>
  </v-app>
</template>

<script>
import HeaderBar from './components/HeaderBar';

export default {
  name: 'App',

  components: {
    HeaderBar
  },

  data: () => ({
    //
  }),
};
</script>
