<template>
    <h1>{{ $translate("greetings.hi") }}</h1>
    <div v-style="{ color: 'blue', fontSize: '40px' }">Hello, world!</div>
</template>
<script setup>
import {inject} from 'vue'

const map = inject('i18n');
console.log(map);
</script>
