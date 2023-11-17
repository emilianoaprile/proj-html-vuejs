<script>
import ServiceItem from './ServiceItem.vue';

export default {
    components: {
        ServiceItem,
    },
    data() {
        return {
            services: [
                {
                    imgSrc: "/img/first-section-img-1.png",
                    flexReverse: false,
                    category: "Business Growth",
                    title: "Increase Brand Awareness",
                    description: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero sint veritatis, hic excepturi aperiam saepe fugit officia suscipit modi, accusantium voluptatem? Quia tempora quam minima accusamus incidunt at veniam aliquam.",
                    consultationLink: "#"
                },

                {
                    imgSrc: "/img/first-section-img-2.png",
                    flexReverse: true,
                    category: "Investors in People",
                    title: "In-House Sales Training",
                    description: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero sint veritatis, hic excepturi aperiam saepe fugit officia suscipit modi, accusantium voluptatem? Quia tempora quam minima accusamus incidunt at veniam aliquam.",
                    consultationLink: "#"
                },

                {
                    imgSrc: "/img/first-section-img-3.png",
                    flexReverse: false,
                    category: "Social Media Analysis",
                    title: "Harness Your Social Proof",
                    description: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero sint veritatis, hic excepturi aperiam saepe fugit officia suscipit modi, accusantium voluptatem? Quia tempora quam minima accusamus incidunt at veniam aliquam.",
                    consultationLink: "#"
                },

            ]
        };
    }
};
</script>


<template>
    <section class="services">
        <div class="container">
            <ServiceItem v-for="(service, index) in services" :key="index" :service="service" />
        </div>

    </section>
</template>

<style scoped>
.services {
    padding-top: 50px;
}
</style>