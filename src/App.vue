<script setup>
import { ref } from 'vue';
const count = ref(0)
</script>

<template>
  <main>
    <div>
      <h4>
        The current coount is...
      </h4>
      <h1>{{ count }}</h1>
      <button @click="count--">-</button>
      <button @click="count++">+</button>
    </div>
  </main >
</template>

<style scoped>
main{
  background-color: aliceblue;
  height: 100vh;
  width: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  color:black;
}

div{
  text-align: center;
}
</style>