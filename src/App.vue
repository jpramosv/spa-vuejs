<template>
  <ReaderTrajar />
  <IntroTrajar />
  <AboutTrajar />
  <ClienteTrajar />
  <AttributesTrajar />
</template>

<script>
import ReaderTrajar from './components/ReaderTrajar.vue';
import AboutTrajar from './components/AboutTrajar.vue';
import IntroTrajar from './components/IntroTrajar.vue';
import ClienteTrajar from './components/ClienteTrajar.vue';
import AttributesTrajar from './components/AttributesTrajar.vue';




export default {
  name: 'App',
  components: {
    ReaderTrajar,
    AboutTrajar,
    IntroTrajar,
    ClienteTrajar,
    AttributesTrajar
  }
}
</script>

<style>

</style>
