<template>
  <div id="app">
    <Navbar/>  
    <Naslovnica/>  
  </div>
</template>

<script>

import Navbar from "./components/Navbar";
import Naslovnica from "./components/Naslovnica"


export default {
  name: 'App',
  components: {
    Navbar,
    Naslovnica
  }
}
</script>

<style>
body {
  background-image: url("https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fweknowyourdreams.com%2Fimages%2Frestaurant%2Frestaurant-01.jpg&f=1&nofb=1");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>