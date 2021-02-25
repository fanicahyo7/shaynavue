<template>
  <div class="home">
   <HeaderShayna />
   <HeroShayna />
   <WomenShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import HeroShayna from '@/components/HeroShayna.vue'
import WomenShayna from '@/components/WomenShayna.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    HeaderShayna,
    HeroShayna,
    WomenShayna
  }
}
</script>
