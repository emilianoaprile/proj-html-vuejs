<script>
export default {
    props: {
        service: {
            type: Object,
            required: true,
        },
    },
}
</script>

<template>
    <div class="service-item">
        <div class="row" :class="{ 'flex-reverse': service.flexReverse }">
            <div class="col-6">
                <figure class="img-wrapper">
                    <img :src="service.imgSrc">
                </figure>
            </div>
            <div class="col-6">
                <div class="service-card">
                    <p>{{ service.category }}</p>
                    <h2 class="card-title">{{ service.title }}</h2>
                    <p class="card-text">{{ service.description }}</p>

                    <div class="button btn-orange">
                        <a :href="service.consultationLink">Get a Consultation</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>


<style scoped>
.service-card {
    width: 70%;
    margin: 0 auto;
    padding: 100px 0;
}

.button {
    width: max-content;
}

.card-title {
    font-size: 44px;
    margin-bottom: 28px;
    margin-top: 28px;
}

.card-text {
    font-size: 17px;
    margin-bottom: 28px;
    line-height: 30px;
}

.service-item {
    padding-top: 100px;
}
</style>
