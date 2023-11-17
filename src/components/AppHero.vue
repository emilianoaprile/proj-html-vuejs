<script>
import FormCard from './FormCard.vue';

export default {
    components: {
        FormCard,
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
    <div class="page-hero">
        <div class="container">
            <div class="row">
                <div class="col-6">
                    <h1 class="hero-title">Unlock Your Online Growth Potential</h1>
                    <p class="hero-subtitle">
                        Online marketing to secure customers retention, leads and sales. We focus on the bigger picture.
                    </p>
                    <span class="button btn-white">
                        <a href="#">
                            Our Services
                            <font-awesome-icon icon="fa-solid fa-arrow-right" />
                        </a>
                    </span>


                </div>
                <div class="col-6">
                    <FormCard />
                </div>
            </div>

        </div>
    </div>
</template>

<style scoped>
.page-hero {
    min-height: 100%;
    width: 100%;
    background-image: url(/img/marketing-intro.jpg);
    background-size: cover;
    padding-top: 100px;
}

.hero-title {
    font-size: 60px;
    color: white;
}

.hero-subtitle {
    color: white;
    margin-top: 40px;
    margin-bottom: 40px;
    padding-right: 200px;
    font-size: 17px;
    line-height: 30px;
}
</style>