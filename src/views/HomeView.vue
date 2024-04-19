<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <main>
    <h1>Fdia Ur Rehman</h1>
    <h3>Vue.js Assignment Task</h3>
    <p>Here only three pages were required </p> 
    <ol>
      <li>Login</li>
      <li>Dashboard</li>
      <li>Otp</li>
    </ol>
    <p> You can check the required pages by clicking on the following buttons</p>
    <RouterLink to="/login" class="btn">Login</RouterLink>
    <RouterLink to="/dashboard" class="btn">Dashboard</RouterLink>
    <RouterLink to="/otp" class="btn">Otp</RouterLink>


  </main>
</template>

<style scoped>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-size: 2rem;
  }

  .btn {
    margin: 1rem;
    padding: 0.5rem 1rem;
    border: 1px solid #000;
    border-radius: 5px;
    text-decoration: none;
    color: #fff;
  }

  .btn {
    background-color: #3CC553;
    padding: 10px 20px;
  }

  .btn:hover {
    background-color: #fff;
    color: #3CC553;
  }
</style>
