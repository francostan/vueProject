<script setup>
let name = 'Franui'

const handleClick = () => {
 console.log('click')
}
</script>

<template>
 <h1 class="text-3xl font-bold underline">
    Hello {{ name }}
  </h1>
  <button @click=handleClick>Cambiar nombre</button>
</template>

<style scoped>
</style>
