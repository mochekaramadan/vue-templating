<template>
  <div class="home">
    <!-- Header Section Begin -->
    <Header />
    <!-- Header End -->

    <!-- Hero Section Begin -->
    <HeroSection />
    <!-- Hero Section End -->

    <!-- Women Banner Section Begin -->
    <WomenBannerSection />
    <!-- Women Banner Section End -->

    <!-- Instagram Section Begin -->
    <InstagramPhotosSection />
    <!-- Instagram Section End -->

    <!-- Partner Logo Section Begin -->
    <PartnerLogoSection  />
    <!-- Partner Logo Section End -->

    <!-- Footer Section Begin -->
    <Footer />
    <!-- Footer Section End -->
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import HeroSection from '@/components/Home/HeroSection.vue'
import WomenBannerSection from '@/components/Home/WomenBannerSection.vue' 
import InstagramPhotosSection from '@/components/Home/InstagramPhotosSection.vue'
import PartnerLogoSection from '@/components/Home/PartnerLogoSection.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    HeroSection,
    WomenBannerSection,
    InstagramPhotosSection,
    PartnerLogoSection,
    Footer
  }
}
</script>
