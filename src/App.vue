<script>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import TheNav from '@/components/Template/TheNav.vue';
import TheFooter from '@/components/Template/TheFooter.vue';

export default {
  components: {
    TheNav,
    TheFooter,
  },

};
</script>

<template>

  <header>
    <TheNav></TheNav>
    <!-- <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink> -->
  </header>
  <main class="main-container d-flex">
    <div class="my-page">
      <RouterView />
    </div>
    <div class="right-container"></div>
  </main>
  <footer>
    <TheFooter></TheFooter>
  </footer>

</template>

<style scoped>
body {
  margin: 0;
}

.right-container {
  width: 20%;
  /* height: 1000px; */
  background-color: antiquewhite;
}

.my-page{
  width: 80%;
  padding: 40px;
  /* height: 1000px; */
  /* background-color: aqua; */
}
</style>
