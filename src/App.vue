<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from "./components/Navbar.vue";
</script>

<template>
  <header>
    <!-- <img alt="Arbracats logo" class="logo" src="@/assets/logo.png" width="125" height="125" /> -->

    <Navbar/>
  </header>
  <RouterView />
</template>

