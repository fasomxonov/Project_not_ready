<template>
  <div>
    <Navigation />
    <FoodCarousel />
    <Partners />
    <Footer />
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import FoodCarousel from '@/components/FoodCarousel'
import Partners from '@/components/Partners'
import Footer from '@/components/Footer'
export default {
  components: {
    Navigation,
    FoodCarousel,
    Partners,
    Footer,
  },

}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: sans-serif;
}
</style>