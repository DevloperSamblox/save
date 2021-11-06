

<template>
  <h1>{{ msg }}</h1>

 

  <p>
    Sendo produzido para a vida de todos.
</p>
</template>


<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})



const state = reactive({ count: 1 })
</script>

<style scoped>
a {
  color: #42b983;
}
p { 
  color: black
}
</style>