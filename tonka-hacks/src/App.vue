<script setup>
  import NavBar from "./components/NavBar.vue"
</script>

<template>
    <header class="nav_bar">
      <NavBar/>
    </header>
    <header>

    </header>
    <header class="trending">
      <Trending/>
    </header>
</template>

<style>
body {
  background-color: #202020;
  font-family: Arial, Helvetica, sans-serif;
}

header.nav_bar {
  height: 95%;
  width: 20%;
  background-color: #272727;
  border-radius: 10px; 
  padding: 10px;
  text-align: center;
  position: absolute;
}

header.content {
  height: 95%;
  width: 70%;
}

header.trending {
  height: 95%;
  width: 20%;
  background-color: #272727;
  border-radius: 10px; 
  padding: 10px;
  text-align: center;
  position: absolute;
  left: 78%;
}
</style>
