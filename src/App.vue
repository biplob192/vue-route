<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav>

  <RouterView />
</template>

<style scoped>
nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
  margin-left: 45px;
}

nav a.router-link-exact-active {
  color: #fff;
  background-color: orangered;
  border-radius: 5px;
}

nav a {
  display: inline-block;
  font-size: 21px;
  text-decoration: none;
  padding: 5px;
  margin: 5px;
  border-left: 1px solid var(--color-border);
}
</style>
