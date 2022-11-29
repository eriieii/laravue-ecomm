<template>
    <div class="ProductView">
      <!-- Header Section Begin -->
        <Header />
      <!-- Header End --> 
      <!-- Breadcrumb Section Begin -->
        <Breadcrumb />
      <!-- End Breadcrumb Section Begin -->
      <!-- Shopping Cart Section Begin -->
        <ShopingCart />
      <!-- End Shopping Cart Section Begin -->
      <!-- Footer Section Begin -->
        <Footer />
      <!-- End Footer Section Begin -->
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import Header from '@/components/Header.vue'
  import Breadcrumb from '@/components/Breadcrumb.vue'
  import ShopingCart from '@/components/ShopingCart.vue'
  import Footer from '@/components/Footer.vue'
  
  
  export default {
    name: 'ProductView',
    components: {
      Header,
      Breadcrumb, 
      ShopingCart,
      Footer
    }
  }
  </script>
  