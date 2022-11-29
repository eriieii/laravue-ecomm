<template>
  <div class="home">
    <!-- Header Section Begin -->
      <Header />
    <!-- Header End --> 
    <!-- Hero Section Begin --> 
      <CarouselHome />
    <!-- Hero Section End -->  
    <!-- Banner Section Begin -->
      <CarouselProduct />
    <!-- End Banner Section Begin -->
    <!-- Footer Section Begin -->
      <Footer />
    <!-- End Footer Section Begin -->
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import CarouselHome from '@/components/CarouselHome.vue'
import CarouselProduct from '@/components/CarouselProduct.vue'
import Footer from '@/components/Footer.vue'


export default {
  name: 'HomeView',
  components: {
    Header,
    CarouselHome,
    CarouselProduct,
    Footer
  }
}
</script>
