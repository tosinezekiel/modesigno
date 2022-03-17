<template>
  <section class="min-h-screen flex flex-col justify-center relative">
    <div
      class="banner1 container flex flex-col justify-center items-center text-center lg:text-left lg:items-start h-full"
    >
      <h1 class="font-semibold text-5xl">Wear it like you mean it.</h1>
      <p class="max-w-lg my-4">
        Everything made out of quality materials for creative enthusiast
        supporting technology at large.
      </p>
      <nuxt-link
        to="/"
        class="
          px-16
          py-4
          font-semibold
          border-2 border-black
          hover:text-white hover:bg-black
        "
      >
        Shop Now
      </nuxt-link>
      <div class="benefits my-4 text-sm flex gap-x-6">
        <span>Free Signup</span>
        <span>No charges</span>
        <span>Over 100+ designs</span>
      </div>
      <div class="categories flex divide-x-2 divide-black absolute bottom-6">
        <span>Men</span>
        <span>Women</span>
        <span>Kids</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
section {
  background-image: url('~/assets/banner_bg.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: right;
}

a {
  transition: 500ms;
}

.categories span {
  @apply px-6
	    text-xs;
}
</style>