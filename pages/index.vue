<template>
  <div>
    <AppHeader />
    <Banner1 />
    <Collections />
    <PopularProducts />
    <Footer />
  </div>
</template>

<script>
import Banner1 from '~/components/Banner1.vue'
import AppHeader from '~/components/AppHeader.vue'
import Collections from '~/components/Collections.vue'
import PopularProducts from '~/components/PopularProducts.vue'
import Footer from '~/components/Footer.vue'
export default {
  components: {
    AppHeader,
    Banner1,
    Collections,
    PopularProducts,
    Footer,
  }
}
</script>

<style>

</style>
