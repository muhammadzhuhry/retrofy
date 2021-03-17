<template>
  <Title />
  <Status />
</template>

<script>
import Status from './components/Status'
import Title from './components/Title'

export default {
  name: 'App',
  components: {
    Status,
    Title
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');

body {
  font-family: 'Press Start 2P', cursive;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
