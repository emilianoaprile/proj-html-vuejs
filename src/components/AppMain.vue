<script>

import AppMainServices from './AppMainServices.vue';
import AppMainBrandList from './AppMainBrandList.vue';
import CtaCard from './CtaCard.vue';
import TrustedSection from './TrustedSection.vue';


export default {
    components: {
        AppMainServices,
        AppMainBrandList,
        CtaCard,
        TrustedSection,
    },
    data() {
        return {

        }
    },
    methods: {

    }
}
</script>


<template>
    <AppMainServices />
    <AppMainBrandList />
    <CtaCard />
    <TrustedSection />
</template>

<style scoped></style>