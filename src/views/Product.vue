<template>
  <div class="home">
    <!-- Header Section Begin -->
    <Header />
    <!-- Header End -->

    <!-- Breadcrumb Section Begin -->
    <Breadcumb />
    <!-- Breadcrumb Section Begin -->

    <!-- Product Shop Section Begin -->
    <ProductShop />
    <!-- Product Shop Section End -->

    <!-- Related Products Section End -->
    <RelatedProduct />
    <!-- Related Products Section End -->

    <!-- Footer Section Begin -->
    <Footer />
    <!-- Footer Section End -->
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import Breadcumb from '@/components/Product/Breadcumb.vue'
import ProductShop from '@/components/Product/ProductShop.vue'
import RelatedProduct from '@/components/Product/RelatedProduct.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Breadcumb,
    ProductShop,
    RelatedProduct,
    Footer
  }
}
</script>
