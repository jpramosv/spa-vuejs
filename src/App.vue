<template>
  <ReaderTrajar />
  <IntroTrajar />
  <AboutTrajar />
  <ClienteTrajar />
  <AttributesTrajar />
  <OfferTrajar />
</template>

<script>
import ReaderTrajar from './components/ReaderTrajar.vue';
import AboutTrajar from './components/AboutTrajar.vue';
import IntroTrajar from './components/IntroTrajar.vue';
import ClienteTrajar from './components/ClienteTrajar.vue';
import AttributesTrajar from './components/AttributesTrajar.vue';
import OfferTrajar from './components/OfferTrajar.vue';




export default {
  name: 'App',
  components: {
    ReaderTrajar,
    AboutTrajar,
    IntroTrajar,
    ClienteTrajar,
    AttributesTrajar,
    OfferTrajar
  }
}
</script>

<style>

</style>
