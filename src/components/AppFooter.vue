<script>
import FooterMenu from './FooterMenu.vue';

export default {
    components: {
        FooterMenu
    },

    data() {
        return {

            footerMenuServices: {
                title: 'Services',
                links: [

                    {
                        text: 'Marketin Plan',
                        href: '#'
                    },

                    {
                        text: 'Sales Developement',
                        href: '#'
                    },

                    {
                        text: 'Digital Marketing',
                        href: '#'
                    },

                    {
                        text: 'Pricing',
                        href: '#'
                    },

                    {
                        text: 'Why Us',
                        href: '#'
                    },

                    {
                        text: 'Case Studies',
                        href: '#'
                    }
                ]

            },

            FooterMenuResources: {
                title: 'Resources',
                links: [
                    {
                        text: 'Learning Center',
                        href: '#'
                    },

                    {
                        text: 'Video Tutorials',
                        href: '#'
                    },

                    {
                        text: 'Customers',
                        href: '#'
                    },

                    {
                        text: 'Blog',
                        href: '#'
                    },
                ]
            },

            FooterMenuCompany: {
                title: 'Company',
                links: [
                    {
                        text: 'Who We Are',
                        href: '#'
                    },

                    {
                        text: 'Contact Us',
                        href: '#'
                    },

                    {
                        text: 'Careers',
                        href: '#'
                    },
                ]
            }

        }

    }
}
</script>



<template>
    <footer class="footer-section">
        <div class="container-lg">
            <nav class="footer-menu flex flex-between">
                <div class="social-links flex flex-column">
                    <h4 class="social-links-title">
                        Grow Your Online Business Strategically, and Improve Customer Retention.
                    </h4>

                    <div class="social-brands-icons flex">
                        <a href="#"><font-awesome-icon icon="fa-brands fa-facebook" /></a>
                        <a href="#"><font-awesome-icon icon="fa-brands fa-x-twitter" /></a>
                        <a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
                        <a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a>
                        <a href="#"><font-awesome-icon icon="fa-brands fa-linkedin" /></a>
                        <a href="#"><font-awesome-icon icon="fa-brands fa-tiktok" /></a>
                    </div>
                </div>

                <FooterMenu :title="footerMenuServices.title" :links="footerMenuServices.links" />
                <FooterMenu :title="FooterMenuResources.title" :links="FooterMenuResources.links" />
                <FooterMenu :title="FooterMenuCompany.title" :links="FooterMenuCompany.links" />
            </nav>
        </div>
    </footer>
</template>

<style>
.footer-section {
    padding-top: 120px;
    padding-bottom: 100px;
    background-color: #f4f4f6;
}

.social-links {
    flex-basis: 40%;
    gap: 35px;
    padding-right: 40px;
}

.social-links-title {
    font-size: 30px;
}

.social-brands-icons {
    gap: 30px;
    font-size: 30px;
}

.navigation-menu-title {
    font-size: 20px;
    margin-bottom: 30px;
}

.navigation-menu {
    gap: 25px;
}

.navigation-links {
    padding-right: 100px;
}

.navigation-menu-item {
    font-size: 17px;
}
</style>