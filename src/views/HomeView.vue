<template>
  <div class="HomeView">
    <MainComtainer>
      <h1>HomePage</h1> 
    </MainComtainer>
  </div>
</template>

<script>
// @ is an alias to /src
import MainComtainer from '@/components/MainComtainer.vue';

export default{
  name: 'HomeView',
  components: {
    MainComtainer,
  }
}
</script>
