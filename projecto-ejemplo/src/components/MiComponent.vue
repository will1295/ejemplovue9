<script setup>
    import {ref} from 'vue';
    let texto = ref("")
</script>

<template>
    <input v-model="texto" type="text" placeholder="Escribe algo">
    <label for="">{{ texto }}</label>

</template>

<style scoped>
</style>