<template>
  <div class="hello">
    a
      <calculator/>
      a
  </div>
</template>

<script>
import Calculator from './Calculator.vue'
export default {
  components: { Calculator },
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

