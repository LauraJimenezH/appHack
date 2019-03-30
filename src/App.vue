<template>
  <div id="app">
    <FormDenuncia/>
  </div>
</template>

<script>
import FormDenuncia from './components/FormDenuncia.vue'

export default {
  name: 'app',
  components: {
    FormDenuncia
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  padding-top: 40px;
  background:  #F9FAFB;
}

input,select, textarea {
  border: none !important;
}
</style>
