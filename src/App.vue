<template>
  <div id="app">
    <div id="nav">
      <router-link to="/"></router-link>
      <router-link to="/about"></router-link>
    </div>
    <router-view />
  </div>
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;700&display=swap");
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
