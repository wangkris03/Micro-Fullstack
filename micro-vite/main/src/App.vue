<script lang="ts" setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <RouterLink to="/">Home</RouterLink> /
  <RouterLink to="/about">About</RouterLink> /

  <RouterLink to="/foo/codespaces">Codespaces (Foo)</RouterLink> /
  <RouterLink to="/foo/marketplace">Marketplace (Foo)</RouterLink> /

  <RouterLink to="/bar">Bar</RouterLink> /

  <RouterLink to="/xxx">404</RouterLink> /
  <RouterLink to="/foo/xxx">404 (Foo)</RouterLink>

  <RouterView />
  <div id="subapp-viewport"></div>
</template>
