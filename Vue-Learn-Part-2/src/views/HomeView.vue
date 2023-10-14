<script setup>
import TheWelcome from '@/components/TheWelcome.vue';


// onMounted(() =>{
//     alert('HIIII')
// });

let message = $ref('hellow world');

setTimeout(()=>{
  message = " I HAVE BEEN CHANGED"
},2000);

let doSomething = () => {
  alert('DOOOO IT NOW')
}

</script>

<template>
  <main>
    <TheWelcome />

    <input type="text" v-model="message">
    <p>{{message}}</p>

    <button @click="doSomething">Click to alert
    </button>
  </main>
</template>
