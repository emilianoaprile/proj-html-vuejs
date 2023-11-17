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

            <ul class="header-nav-menu flex flex-between align-center">

                <li v-for="(menuItem, index) in headerMenu" :key="index" class="nav-menu-item"
                    :class="{ 'button': menuItem.isButton, 'btn-light-orange': menuItem.isButton }">
                    <a class="flex align-center" :href="menuItem.href">
                        <img v-if="menuItem.imgSrc" :src="menuItem.imgSrc" alt="" />
                        <span style="padding: 0px 10px;" v-if="menuItem.text !== '(555) 802-1234'">{{ menuItem.text
                        }}</span>
                        <font-awesome-icon :class="{ 'orange-icon': menuItem.iconColor === 'orange' }" v-if="menuItem.icon"
                            :icon="menuItem.icon" />
                        <span style="padding: 0 10px;" v-if="menuItem.text === '(555) 802-1234'">{{ menuItem.text }}</span>
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

.orange-icon {
    color: rgb(247, 96, 18);
    ;
}
</style>