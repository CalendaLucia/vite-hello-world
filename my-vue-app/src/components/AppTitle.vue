<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})


</script>

<template>
  <h3>{{ msg }}</h3>
</template>


