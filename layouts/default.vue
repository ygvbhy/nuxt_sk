<template>
  <div>
    <header-layout></header-layout>
    <nuxt />
    <footer-layout></footer-layout>
  </div>
</template>

<script>
import HeaderLayout from '@/components/HeaderLayout.vue'
import FooterLayout from '@/components/FooterLayout.vue'
export default {
  components: {
    HeaderLayout,
    FooterLayout,
  },
}
</script>

<style lang="scss" scoped></style>
