<script setup>
  import NavBar from "./components/NavBar.vue"
  import Trending from "./components/Trending.vue"
  import Content from "./components/Content.vue"
</script>

<template>
    <header class="nav_bar">
      <NavBar/>
    </header>
    <header class="content">
      <Content/>
    </header>

    <div class="post_button">
        <text class="post_button_text">Post</text>
    </div>

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
  width: 52.3%;
  position: absolute;
  padding: 10px;
  border-color: white;
  border-width: 3px;
  border-style: solid;
  left: 23%;
  z-index: 0;
  display: inline-flex;
  align-items: center;
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

div.post_button {
  background-color: #1e8337;
  width: 10%;
  height: 20px;
  text-align: center;
  padding: 10px;
  border-radius: 5px;
  position: absolute;
  top: 90%;
  left: 65%;
}  
text.post_button_text {
  font-size: 20px;
  color: #222222;
} 
</style>
