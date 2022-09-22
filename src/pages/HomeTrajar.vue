<template>
    <ReaderTrajar />
    <IntroTrajar />
    <AboutTrajar />
    <ClienteTrajar />
    <AttributesTrajar />
    <OfferTrajar />
    <ProductsTrajar />
    <BriefTrajar />

</template>
  
<script>
import ReaderTrajar from '../components/ReaderTrajar.vue';
import IntroTrajar from '../components/IntroTrajar.vue';
import AboutTrajar from '../components/AboutTrajar.vue';
import ClienteTrajar from '../components/ClienteTrajar.vue';
import AttributesTrajar from '../components/AttributesTrajar.vue';
import OfferTrajar from '../components/OfferTrajar.vue';
import ProductsTrajar from '../components/ProductsTrajar.vue';
import BriefTrajar from '../components/BriefTrajar.vue';



export default {
    name: 'HomeTrajar',
    components: {
        ReaderTrajar,
        IntroTrajar,
        AboutTrajar,
        ClienteTrajar,
        AttributesTrajar,
        OfferTrajar,
        ProductsTrajar,
        BriefTrajar
    }
}
</script>