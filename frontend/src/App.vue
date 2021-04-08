<template>

  <v-app>
   <v-toolbar app>
     
    </v-toolbar>

    <v-main>
    <messages />
    </v-main>
  </v-app>

</template>

<script>
import Messages from './components/Messages.vue';

export default {
  name: 'App',

  components: {
    Messages,
  },

  data: () => ({
    //
  }),
};
</script>
