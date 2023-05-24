<template>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
  <HeaderList msg="Welcome to Your Vue.js App❤❤ Mother Fuckers!❤❤"/>
  <div class = "container">
  <HiYeah></HiYeah>
  <list_of></list_of>
  <Infomration_list></Infomration_list>
  </div>
</template>

<script>
import HeaderList from './components/Header_list.vue'
import HiYeah from './components/Hi_yeah.vue'
import list_of from './components/Hi2yeet.vue'
import Infomration_list from "@/components/Infomration_list.vue";
export default {
  name: 'App',
  components: {
    HeaderList,
    HiYeah,
    list_of,
    Infomration_list,
  },
}
</script>

<style>
#app {
  overflow: auto;
  scroll-snap-type: y mandatory;
  height: 100vh;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: LightPink;
  font-family: sans-serif;
  margin-top: 0px;
  background-size: cover;
  background-color: #ECCDB4;
  background-repeat: no-repeat;
  background-position: center center;

/*@media (max-width: 700px) {*/
/*  .title {*/
/*    font-size: 4rem;*/
/*  }*/

/*  p {*/
/*    padding: 0 1rem;*/
/*  }*/

/*  p,*/
/*  .menu-list li {*/
/*    font-size: 1rem;*/
/*  }*/

/*  .hero {*/
/*    padding-top: 12vh;*/
/*  }*/
/*}*/

}
</style>
