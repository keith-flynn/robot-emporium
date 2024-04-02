<template>
  <header>
    <nav>
      <ul>
        <li class="nav-item">
          <img class="logo" src="./assets/robot-emporium-logo.png" alt="logo" />
          Robot Emporium
        </li>
      </ul>
    </nav>
  </header>
  <main>
    <!-- <HomePage msg="Welcome to Your Vue.js App"/> -->
    <router-view />
  </main>
</template>

<script setup>
// import { ref, provide } from 'vue';

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}

body {
  background: linear-gradient(to bottom, #555, #999);
  background-attachment: fixed;
}
</style>

<style scoped>
main {
  margin: 0 auto;
  padding: 30px;
  background-color: white;
  width: 1000px;
  min-height: 300px;
}

header {
  background-color: #999;
  width: 1000px;
  margin: 0 auto;
}

ul {
  padding: 3px;
  display: flex;
}

.nav-item {
  display: inline-block;
  padding: 5px 10px;
  font-size: 22px;
  border-right: 1px solid #bbb;
}

.logo {
  vertical-align: middle;
  height: 30px;
}
</style>
./components/HomePage.vue
