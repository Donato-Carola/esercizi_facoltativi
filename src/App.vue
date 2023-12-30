<template>
  <section>
 <AppHeader/>  
 <AppMain/>
</section>
</template>



<script >
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
export default {
 data() {
  return {
    
  }
 },
 components:{
  AppHeader,
  AppMain,
 }
}
</script>










<style lang="scss">
@use "./styles/general.scss" as *;

section{
  background-color: rgb(39, 39, 39);
}
</style>
