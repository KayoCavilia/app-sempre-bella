<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import NavSidebar from './components/layout/NavSidebar.vue';
import HeaderBar from './components/layout/HeaderBar.vue';
import BreadCrumb from './components/layout/BreadCrumb.vue';
</script>

<template>
  <NavSidebar/>
  <HeaderBar/>

  <div class="pc-container">
    <div class="pc-content">

      <BreadCrumb/>
      <RouterView />
    </div>
  </div>

  <FooterBar/>
</template>

<style scoped>
</style>
