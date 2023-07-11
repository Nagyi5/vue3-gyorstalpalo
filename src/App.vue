<script setup>
  import Welcome from './components/Welcome.vue';
</script>

<template>
  <header></header>
  <main>
    <Welcome />
  </main>
  <footer></footer>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Quicksand&display=swap');

:root {
--blue:#576ca8;
--inputBg:#444b67;
--cr1:#c94277;
--cr2:#1b998b;
--cr3:#ffd046;

}

body {
  background-color: #302b27;
  color: #fff;
}
#app {
  font-family: Quicksand, sans-serif;
}

main{
  padding: 0.5rem;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.df{
  display: flex;
  gap: 1rem;
}
</style>
