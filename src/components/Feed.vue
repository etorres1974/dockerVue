<template>
  <div>
    <div class="pa-2" v-for="n in 2" :key="n">
      <message/>
    </div>
  </div>
</template>

<script>
import Message from "./Message.vue";

export default {
  components: { Message },
  name: "Feed",
  data() {
    return {};
  },
  methods: {},
};
</script>
