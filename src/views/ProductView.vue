<template>
    <div class="ProductView">
      <!-- Header Section Begin -->
        <Header />
      <!-- Header End --> 
      <!-- Breadcrumb Section Begin -->
        <Breadcrumb />
      <!-- End Breadcrumb Section Begin -->
      <!-- Product Shop Section Begin -->
        <ProductDetail />
      <!-- End Product Shop Section Begin -->
      <!-- Related Products Section End -->
      <RelatedProduct />
      <!-- Related Products Section End -->
      <!-- Footer Section Begin -->
        <Footer />
      <!-- End Footer Section Begin -->
    </div>
  </template>
  
  <script>
  // @ is an alias to /src
  import Header from '@/components/Header.vue'
  import Breadcrumb from '@/components/Breadcrumb.vue'
  import ProductDetail from '@/components/ProductDetail.vue'
  import RelatedProduct from '@/components/RelatedProduct.vue'
  import Footer from '@/components/Footer.vue'
  
  
  export default {
    name: 'ProductView',
    components: {
      Header,
      Breadcrumb, 
      ProductDetail, 
      RelatedProduct,   
      Footer
    }
  }
  </script>
  