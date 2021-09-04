<template>

  <v-app class="base">
    <v-main>
      <!-- Provides the application the proper gutter -->
      <v-container >
        <h2 class="title">A Magnífica Calculadora Distribuída</h2>
        <!-- If using vue-router -->
        <router-view></router-view>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",
};

//
</script>

<style >
.base {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #d9efff;
  height: 100vh;
  color: #484848;
}


.title{
  text-align: center;
  padding-bottom: 30px;
}
</style>
