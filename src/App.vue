<template>
  <div class="wrap d-flex flex-column min-vh-100">
    <Header/>
    
    <main class="flex-fill">
      <router-view/>
      
    </main>
    <MainPage/>
    <MainPageGall></MainPageGall>

    <FooterSite/>
   
    
  </div>
  
</template>

<script>
  import Header from '@/components/Header.vue'
  import FooterSite from '@/components/FooterSite.vue'
  import MainPage from '@/components/MainPage.vue'
  import MainPageGall from './components/MainPageGall.vue'
  import '../node_modules/swiper/'
  

  
  
  
  export default{
    components: {
      Header,
      FooterSite,
      MainPage,
      MainPageGall,
     
    },
  }

</script>

<style lang="scss">
*{
    font-family: 'Fira Sans';
    font-style: normal;
    font-weight: 500;
    
}

</style>
