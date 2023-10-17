<script setup>

import {ref} from "vue";

let food = ref('');

// let age = ref('')

function write(){
  localStorage.setItem('food', food.value);
}

</script>

<template>
  <main>
  <div class="about">
    What is your favorite food ? <input type="text" v-model="food" @input="write">
    <br>
<!--    Whats Your Age ? <input type="text" v-model="age">-->
  </div>
  </main>
</template>
