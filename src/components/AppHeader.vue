<script>
export default {
    data() {
        return {
            headerMenu: [
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
                    icon: 'fa-solid fa-phone'

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

            <ul class="header-nav-menu flex flex-between align-center">

                <li v-for="(menuItem, index) in headerMenu" :key="index" class="nav-menu-item"
                    :class="{ 'button': menuItem.isButton, 'btn-light-orange': menuItem.isButton }">
                    <a :href="menuItem.href">
                        <img v-if="menuItem.imgSrc" :src="menuItem.imgSrc" alt="" />
                        <span v-if="menuItem.text !== '(555) 802-1234'">{{ menuItem.text }}</span>
                        <font-awesome-icon v-if="menuItem.icon" :icon="menuItem.icon" />
                        <span v-if="menuItem.text === '(555) 802-1234'">{{ menuItem.text }}</span>
                    </a>
                </li>

            </ul>

        </nav>

    </header>
</template>

<style scoped>
.page-header {
    padding-top: 35px;
    padding-bottom: 35px;
}
</style>