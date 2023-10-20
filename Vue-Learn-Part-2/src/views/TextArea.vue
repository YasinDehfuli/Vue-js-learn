<!-- tab function -->
<script setup>
import TabbabaleTextarea from "@/components/TabbabaleTextarea.vue";
import {ref} from "vue";

let comment = ref('Please enter your text here');

setTimeout(() => {
  comment.value = 'It Works !!!'
},4000)
</script>

<template>
  <main>
  <tabbabale-textarea v-model="comment" />
  </main>
</template>
