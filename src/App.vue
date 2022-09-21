<template>
  <ReaderTrajar />
  <IntroTrajar />
  <AboutTrajar />
  <ClienteTrajar />
</template>

<script>
import ReaderTrajar from './components/ReaderTrajar.vue';
import AboutTrajar from './components/AboutTrajar.vue';
import IntroTrajar from './components/IntroTrajar.vue';
import ClienteTrajar from './components/ClienteTrajar.vue';




export default {
  name: 'App',
  components: {
    ReaderTrajar,
    AboutTrajar,
    IntroTrajar,
    ClienteTrajar
  }
}
</script>

<style>

</style>
