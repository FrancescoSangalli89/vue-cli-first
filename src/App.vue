<template>
  <div id="app">
    <MyTitle />
    <MyHero />

  </div>
</template>

<script>
import MyTitle from '@/components/MyTitle.vue'
import MyHero from '@/components/MyHero.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    MyHero
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
