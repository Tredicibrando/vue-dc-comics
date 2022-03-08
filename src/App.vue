<template>
  <div id="app">
    <MyHeader />
    <MyJumbo />
    <MyCta />
    <MyFooter />
  </div>
</template>

<script>
import MyHeader from '@/components/MyHeader'
import MyJumbo from '@/components/MyJumbo'
import MyCta from '@/components/MyCta'
import MyFooter from '@/components/MyFooter'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyJumbo,
    MyCta,
    MyFooter,
  }
}
</script>

<style lang="scss">

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'PT Sans Narrow', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
