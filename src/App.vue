<template>
  <div id="app">
    <router-view/>

    <!-- {{ msg }}

    <div @click="goto">
      kkkkkk
    </div> -->
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      msg: 222
    }
  },
  methods: {
    goto() {
      // console.log('goto')
    }
  },
  created() {
    // this.$toast('1111')
  }
})
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
