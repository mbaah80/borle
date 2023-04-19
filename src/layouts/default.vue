<template>
<div>
    <Header/>
  <main>
    <slot></slot>
  </main>
    <Footer/>
</div>
</template>
<script>
import Header from '@/components/header/index.vue'
import Footer from '@/components/footer/index.vue'
export default {
  components: {Header, Footer},
  name: "default"
}
</script>

<style scoped>

</style>
