<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="@/assets/logo.png" alt="#" width="60" height="60"></a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item" v-for="(menu, index) in headerMenuList" :key="index">
            <router-link class="nav-link active" aria-current="page" :to="menu.path">
              {{ menu.name }}
            </router-link>
          </li>
        </ul>
       <div>
        
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            
            <li class="nav-item" v-for="(menu, index) in headerMenuList2" :key="index">
              <router-link class="nav-link active" aria-current="page" :to="menu.path">
                {{ menu.name }}
              </router-link>
              
            </li>
          </ul>
        </div>
       </div>
      </div>
    </div>
  </nav>
 
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data(){
    return{
      headerMenuList: [
        { name: 'Review', path: './' },
        { name: 'Possibilities', path: './' },
        { name: 'Plot', path: './' },
        { name: 'News', path: './' },
      ],
      headerMenuList2: [
        { name: 'Sign', path: './' },
        { name: 'Buy', path: './' },
      ]
    }
  },
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

*{
  font-family: 'Fira Sans';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 34px;
  
}
.navbar{
  color: black;
}

</style>
