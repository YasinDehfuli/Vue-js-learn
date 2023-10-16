<script setup>

import {useFlash} from "@/composables/useFlash";

let {flash} = useFlash();

</script>

<template>
  <main>
    <button @click="flash('Success','WELL DONE','info')">Click to alert
    </button>
  </main>
</template>
