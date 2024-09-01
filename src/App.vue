<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="block ">
    <header>

      <div class="wrapper">
        <HelloWorld msg="Randomaister" />

        <nav>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/about">About</RouterLink>
        </nav>
      </div>
    </header>
  </div>


  <RouterView />
</template>

<style scoped>

</style>
