<script>

import AppMainServices from './AppMainServices.vue';
import AppMainBrandList from './AppMainBrandList.vue';
import CtaCard from './CtaCard.vue';
import CaseStudies from './CaseStudies.vue';
import ThingsHappen from './ThingsHappen.vue';


export default {
    components: {
        AppMainServices,
        AppMainBrandList,
        CtaCard,
        CaseStudies,
        ThingsHappen,
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
    <ThingsHappen />
</template>

<style scoped></style>