<template>
  <headerComponent />
  <mainComponent />
  <footerComponent />
</template>

<script>
import headerComponent from './components/headerComponent.vue';
import footerComponent from './components/footerComponent.vue';
import mainComponent from './components/mainComponent.vue';

export default {
  components: {
    headerComponent,
    mainComponent,
    footerComponent
  }
}
</script>

<style lang="scss" scoped>

</style>