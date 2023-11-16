<script>

import AppMainServices from './AppMainServices.vue';
import AppMainBrandList from './AppMainBrandList.vue';
import CtaCard from './CtaCard.vue';


export default {
    components: {
        AppMainServices,
        AppMainBrandList,
        CtaCard,
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
</template>

<style scoped></style>