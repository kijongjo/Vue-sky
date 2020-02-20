<template>
  <div id="app">
    <SkyHeaderBar></SkyHeaderBar>
    <SkyList></SkyList>
    <SkyData></SkyData>
    <SkyFooter></SkyFooter>
  </div>
</template>

<script>
import SkyData from './components/SkyData.vue'
import SkyFooter from './components/SkyFooter.vue'
import SkyHeaderBar from './components/SkyHeaderBar.vue'
import SkyList from './components/SkyList.vue'
 
export default {
   components:{
     
    'SkyData':SkyData,
    'SkyFooter':SkyFooter,
    'SkyHeaderBar':SkyHeaderBar,
    'SkyList':SkyList


   }
};
</script>

<style>
* {
  letter-spacing: 0.01em;
  margin: 0;
  padding: 0;
}

body {
  font-family: "Roboto", sans-serif;
  font-size: 100%;
  /*글자간 간격*/
  line-height: 1.7;
  /* background-color: #fff;*/
}
#app {
  margin-top: 3em;
  /*   background-color: aqua; */

  width: 100%;
}
</style>
