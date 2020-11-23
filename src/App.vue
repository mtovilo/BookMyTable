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