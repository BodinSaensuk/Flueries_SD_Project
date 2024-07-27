<template>
  <div class="flex flex-col min-h-screen w-full">
    <Header />
    <main class="flex-grow">
      <router-view />
    </main>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  },
};
</script>

<style>
/* Add any global styles here if needed */
</style>
