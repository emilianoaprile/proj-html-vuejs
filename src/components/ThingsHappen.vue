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
}
</script>


<template>
    <section class="proof-section">
        <div class="container-lg">
            <div class="row">
                <div class="col-6">
                    <div class="review">
                        <h2 class="review-title">Let's Make Things Happen</h2>
                        <p class="review-subtitle">
                            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Totam molestiae libero deleniti
                            repellat,
                            voluptas, minus sequi non, eius voluptate nihil voluptatum tenetur adipisci cupiditate
                            provident.
                            Hic eum dolorem obcaecati perferendis.
                        </p>
                    </div>

                    <div class="citation">
                        <p class="ceo-cite">
                            <cite>
                                "The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential
                                online and offline. We have experienced year on year growth due to their progressive
                                approach."
                            </cite>
                        <blockquote class="testimonial">George Anderson</blockquote>
                        </p>
                        <p class="testimonial-rule">DigitalBox CEO</p>
                    </div>
                </div>


                <div class="col-6">
                    <FormCard />
                </div>
            </div>

        </div>
    </section>
</template>

<style scoped>
.proof-section {
    background-color: black;
    padding: 100px 0;
}

.card {
    margin-bottom: unset;
}

.review,
.citation {
    color: white;
    padding-right: 130px;
}

.review-title {
    font-size: 60px;
    margin-bottom: 30px;
}

.review-subtitle {
    font-size: 22px;
    opacity: 0.8;
    line-height: 30px;
}

.review::after {
    content: '';
    border-bottom: 1px solid white;
    display: block;
    width: 100px;
    margin-top: 30px;
    margin-bottom: 30px;
}

.ceo-cite {
    font-size: 17px;
    margin-bottom: 30px;
    opacity: 0.8;
}

.testimonial {
    font-weight: 600;
    font-size: 17px;
    margin-bottom: 10px;
    opacity: 0.8;
}

.testimonial-rule {
    font-size: 13px;
    opacity: 0.8;
}
</style>