<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <HelloWorld msg="Hello World!"/>
    <button type="button" v-on:click="alertMe">Alert Me</button>
    <Form/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

import Form from './components/form.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Form
  },
  methods: {
    alertMe() {
      alert('test');
    }
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
