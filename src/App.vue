<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
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

.wrapper
{
  width: 400px;
  border: 2px dashed black;
  text-align: center;
}
.image
{
  width: 400px;
}
button
{
  padding: 12px;
  font-size: 20px;
}
button:hover 
{
  background-color: orange;
}
button:active
{
  background-color: black;
}
@media (max-width: 600px)
{
  .wrapper{background-color: #f3d4a1;}
}
@media (max-width: 400px)
{
  .details{display: none;}
}


</style>
