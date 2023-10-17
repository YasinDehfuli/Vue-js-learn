<script setup>

import {useFlash} from "@/composables/useFlash";

let {flash} = useFlash();

</script>

<template>
  <main>
  <div class="about">
    <button @click="flash('LALALLAL','HOOOOG JOIB NBABE', 'warning')">About Alert</button>
  </div>
  </main>
</template>
