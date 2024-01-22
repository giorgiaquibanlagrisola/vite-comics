<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  data() {
    return { count: 0 }
  },
  components: {
    AppHeader,
    AppMain,
    AppFooter
  }
}
</script>

<template>
    <div>
        <AppHeader />
        <AppMain />
        <AppFooter />
    </div>
</template>

<style scoped>

</style>
