<template>
  <div class="wrap d-flex flex-column min-vh-100">
    <Header/>
    <main class="flex-fill">
      <router-view/>
    </main>
    <FooterSite/>
   
    
  </div>
  
</template>

<script>
  import Header from '@/components/Header.vue'
  import FooterSite from '@/components/FooterSite.vue'
  
  export default{
    components: {
      Header,
      FooterSite,
    },
  }

</script>
<style lang="scss">


</style>
