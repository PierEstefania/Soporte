<template>
  <v-app>
    <Header/> 

    <v-main>
      
    </v-main>
  </v-app>
</template>

<script>
 import Header from './components/Header/Header';

export default {
  name: 'App',

  components: {
     Header,
  },

  data: () => ({
    //
  }),
};
</script>
