<template>
  <div id="app">
    <Panels/>
  </div>
</template>

<script>
import Panels from './components/Panels'

export default {
  name: 'App',
  components: {
    Panels
  }
}
</script>

<style>
html {
      box-sizing: border-box;
      background:#ffc600;
      font-family:'helvetica neue';
      font-size: 20px;
      font-weight: 200;
    }
    body {
      margin: 0;
    }
    *, *:before, *:after {
      box-sizing: inherit;
    }
</style>
