<template>
  <h1>{{ msg }}</h1>

<!-- My custom code -->

<div class="buttons">
  <button class="duplicateButton">Duplicate</button>
  <button class="deleteButton">Delete</button>
  <button class="changeNameButton">Change Name</button>
</div>

<div class="wrapper">
  
    <img class="image" src="https://cdn.dribbble.com/users/902228/screenshots/5813718/media/539d18b06ff32a69bb74f95b78cf6602.jpg?compress=1&resize=400x300"/>
  
  <div class="header">
    <h1>Charizard</h1>
  </div>
  
  <div class="details">
    <details>
      <summary>About this Pokemon</summary>
      <p>
        Charizard is a Fire/Flying type Pokémon introduced in Generation 1. It is known as the Flame Pokémon. Charizard has two Mega Evolutions available in its X & Y forms. In in Mega evolved form, Charizard is arguably the most powerful pokemon
      </p>
    </details>
    
  </div>
  
</div>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<!-- 



<script>

export default {
  methods: {
    hoover() {
      document.querySelectorAll(".card").forEach((item) => {
        if(!item.classList.contains("hoverCard")){
          item.classList.add("hoverCard");
          console.log(item);
        }
        else{
          item.classList.remove("hoverCard");
          console.log(item);
        }
      });
    },
    
    duplicate() {
      const cloneCard = document.querySelector(".card").cloneNode(true);
      document.body.appendChild(cloneCard);
      console.log(cloneCard);    
    },

    background() {
      document.querySelectorAll(".card").forEach((item) => {
        if(!item.classList.contains("basic")){
          item.classList.add("basic");
          console.log(item);
        }
        else{
          item.classList.remove("basic");
          console.log(item);
        }
      });
    },

    heading() {
      document.querySelectorAll(".title").forEach((item) => {   
        if(item.innerHTML=="something else"){
          item.innerHTML="Chad of Cyber IST";
        }
        else{
          item.innerHTML="something else";
        }
      });
    },

    //Kinda borked rn
    deleter(){
      document.querySelector(".card:last-child").remove();
      console.log(card);
    }
  }
}
</script>

-->

<style scoped>
a {
  color: #42b983;
}
</style>
