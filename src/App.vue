<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <div id="nav">
    <router-link to="/">Inicio</router-link>
    <router-link to="/brazil">Brasil</router-link>
    <router-link to="/about">Acerca de</router-link>
  </div>
  <div class="container">
    <RouterView />
  </div>
</template>

<style scoped>
</style>
