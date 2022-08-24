<template>
<div>
  <HelloWorld msg="Welcome to you nft app"/>
  <hr>
  <FileUpload />

</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FileUpload from './components/FileUpload.vue';

export default {
      name: 'App',
      components: {
        HelloWorld,
        FileUpload,
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
