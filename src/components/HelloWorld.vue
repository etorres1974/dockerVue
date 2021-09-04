<template>
  <div>
    <v-row>
      <v-col cols="6">
        <calculator />
      </v-col>
      <v-col cols="6">
        <feed />
      </v-col>
    </v-row>
  </div>
</template>

<script>
import Calculator from "./Calculator.vue";
import Feed from "./Feed.vue";
export default {
  components: { Calculator, Feed },
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App",
    };
  },
};
</script>

