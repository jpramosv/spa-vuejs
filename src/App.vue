<template>
<ReaderTrajar/>
<IntroTrajar/>
<AboutTrajar/>
</template>

<script>
import ReaderTrajar from './components/ReaderTrajar.vue';
import AboutTrajar from './components/AboutTrajar.vue';
import IntroTrajar from './components/IntroTrajar.vue';



export default {
  name: 'App',
  components: {
    ReaderTrajar,
    AboutTrajar,
    IntroTrajar
}
}
</script>

<style>

</style>
