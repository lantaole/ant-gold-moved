<template>
  <div id="app">
    <top></top>
    <router-view></router-view>
  </div>
</template>


<script>
import Top from "../src/components/Top"

export default {
  components: {
    Top: Top,
  },
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">

</style>
