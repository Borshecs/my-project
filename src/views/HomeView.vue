<template>
  <div class="HomeView">
    <MainComtainer>
    
    </MainComtainer>
    
  </div>
</template>

<script>
// @ is an alias to /src
import MainComtainer from '@/components/MainContainer.vue';


export default{
  name: 'HomeView',
  components: {
    MainComtainer,
   
  }
}
</script>

<style>
.HomeView{
  
  background-image: url('@/assets/00009-1243608673\ 3.png');
  width: 100%;
  height: 1168px;
  color: white;
  font-family: 'Fira Sans';
  font-style: normal;
  font-weight: 400;

  line-height: 34px;
  
  
}

</style>
