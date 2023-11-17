<script>
import HeaderMenu from './HeaderMenu.vue';

export default {
    components: {
        HeaderMenu,
    },
    data() {
        return {
            menu: [
                {
                    imgSrc: '/img/avada-marketing-logo-2x-200x37.png',
                    href: '#',
                    icon: ''

                },

                {
                    text: 'Home',
                    href: '#',
                    icon: 'fa-solid fa-chevron-down'
                },

                {
                    text: 'Services',
                    href: '#',
                    icon: 'fa-solid fa-chevron-down'
                },

                {
                    text: 'Why Us',
                    href: '#',
                    icon: ''
                },

                {
                    text: 'Case studies',
                    href: '#',
                    icon: ''

                },

                {
                    text: 'About',
                    href: '#',
                    icon: ''
                },

                {
                    text: 'Blog',
                    href: '#',
                    icon: ''
                },

                {
                    text: '(555) 802-1234',
                    href: '#',
                    icon: 'fa-solid fa-phone',
                    iconColor: 'orange'

                },

                {
                    text: 'Free Quote',
                    href: '#',
                    isButton: true
                }
            ],

        }
    }
}
</script>

<template>
    <header class="page-header">

        <nav class="container-lg">
            <HeaderMenu :headerMenu="menu" />
        </nav>

    </header>
</template>

<style>
.page-header {
    padding-top: 35px;
    padding-bottom: 35px;
}

.orange-icon {
    color: rgb(247, 96, 18);
    ;
}
</style>