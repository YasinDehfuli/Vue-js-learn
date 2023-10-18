<script setup>

import {useStorage} from "@/composables/useStorage";

let food =  useStorage('food');
let age =  useStorage('age');


</script>

<template>
  <main>
  <div class="about">
    What is your favorite food ? <input type="text" v-model="food">
    <br>
    Whats Your Age ? <input type="text" v-model="age">
  </div>
  </main>
</template>
