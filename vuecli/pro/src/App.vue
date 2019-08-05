<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">电影</router-link> |
    </div>
    <router-view/>
  </div>
</template>
<script>
import Navgation from"@/components/Navgation.vue"
export default {
  components:{
    Navgation
  }
}
</script>
<style>
  *{
    margin: 0;
    padding: 0;
  }
  a{
    
  }
</style>
