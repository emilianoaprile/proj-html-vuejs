<script>

import AppMainServices from './AppMainServices.vue';
import AppMainBrandList from './AppMainBrandList.vue';
import CtaCard from './CtaCard.vue';
import CaseStudies from './CaseStudies.vue';


export default {
    components: {
        AppMainServices,
        AppMainBrandList,
        CtaCard,
        CaseStudies,
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
    <CaseStudies />
</template>

<style scoped></style>