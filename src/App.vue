<script setup>
  import { ref } from 'vue'
  const count = ref(0)
  console.log(count);
  
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
button {
  font-weight: bold;
  background-color: red;
  padding: 10px 20px;
  border: none;
  display: inline-block;
  border-radius: 5px;

}
</style>


