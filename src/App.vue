<template>
  <div class="">
    <TopBarVue />
    <onContainer />
  </div>
</template>

<script>
import TopBarVue from '@/components/TopBar.vue'
import onContainer from '@/components/Container.vue'

export default {
  name: 'App',
  components: {
    TopBarVue,
    onContainer,
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
}
</style>
