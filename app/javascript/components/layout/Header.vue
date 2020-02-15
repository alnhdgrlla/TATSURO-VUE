<template>
  <header class="header">
    <h1>Employee Index</h1>
    <router-link to="/"> See all employees </router-link>
    <router-link to="/employees/new"> Create new employee </router-link>
  </header>
</template>

<script>
export default {
    name: "Header"
  }
</script>

<style scoped>
  .header {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
  }

  .header a{
    color: #fff;
    padding-right: 5px;
  }
</style>