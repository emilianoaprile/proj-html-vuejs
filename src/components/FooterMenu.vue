<script>
export default {
    props: ['title', 'links']
}
</script>


<template>
    <div class="navigation-links">
        <h6 class="navigation-menu-title">{{ title }}</h6>
        <ul class="navigation-menu flex flex-column">
            <li class="navigation-menu-item" v-for="(link, index) in links" :key="index">
                <a :href="link.href">{{ link.text }}</a>
            </li>
        </ul>
    </div>
</template>

<style scoped lang="scss">
.navigation-links {
    padding-right: 100px;

    .navigation-menu-title {
        font-size: 20px;
        margin-bottom: 30px;
    }

    .navigation-menu {
        gap: 25px;
    }

    .navigation-menu-item {
        font-size: 17px;
    }
}
</style>