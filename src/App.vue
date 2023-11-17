<script>
import AppHeader from './components/AppHeader.vue';
import AppHero from './components/AppHero.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppHero,
    AppMain,
    AppFooter,
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
  <AppHeader />
  <AppHero />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss">
@use './style/general.scss';

// google font
@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed");
</style>
