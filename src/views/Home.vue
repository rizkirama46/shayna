<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBanner />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomenBanner from '@/components/WomenBanner.vue';
import InstaShayna from '@/components/InstaShayna.vue';
import PartnerShayna from '@/components/PartnerShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroShayna,
    WomenBanner,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>
