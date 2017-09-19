<template>
  <div id="app">
    <hello></hello>
  </div>
</template>

<script>
import Hello from './components/Hello';

export default {
  name: 'app',
  components: {
    Hello,
  },
};
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;
}

html {
  height: 100%;
}

body {
  background: -moz-linear-gradient(45deg, rgba(225,226,227,1) 0%, rgba(163,200,255,1) 100%); /* ff3.6+ */
  background: -webkit-gradient(linear, left bottom, right top, color-stop(0%, rgba(225,226,227,1)), color-stop(100%, rgba(163,200,255,1))); /* safari4+,chrome */
  background: -webkit-linear-gradient(45deg, rgba(225,226,227,1) 0%, rgba(163,200,255,1) 100%); /* safari5.1+,chrome10+ */
  background: -o-linear-gradient(45deg, rgba(225,226,227,1) 0%, rgba(163,200,255,1) 100%); /* opera 11.10+ */
  background: -ms-linear-gradient(45deg, rgba(225,226,227,1) 0%, rgba(163,200,255,1) 100%); /* ie10+ */
  background: linear-gradient(45deg, rgba(225,226,227,1) 0%, rgba(163,200,255,1) 100%); /* w3c */
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#A3C8FF', endColorstr='#E1E2E3',GradientType=1 ); /* ie6-9 */
  height: 100%;
}
</style>
