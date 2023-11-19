<script>
export default {
    props: {
        headerMenu: {
            type: Array,
            required: true,
        }
    },

}
</script>


<template>
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
        <!-- 
        <li :class="{ 'button': menuItem.isButton, 'btn-light-orange': menuItem.isButton }">
            {{ menuItem.text }}
        </li> -->

    </ul>
</template>
