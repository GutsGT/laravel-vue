<script setup>
    import {ref} from "vue";
    const name = ref("");
</script>

<template>
    <h2>Hello Vue.js</h2>
    {{ name }}
    <input type="text" v-model="name">
</template>