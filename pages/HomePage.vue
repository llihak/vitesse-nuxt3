<template>
  <main
    id="HomePage"
    class="max-w-5xl mx-auto"
  >
    <Overview></Overview>
    <Products></Products>

  </main>
</template>


<script>
definePageMeta({
  layout: 'mylayout'
})
export default {
  name: 'HomePagePage'
}
</script>
<style>
.button {
  @apply mx-auto text-white text-center px-4 py-1 rouned-md shadow-lg;
}
</style>