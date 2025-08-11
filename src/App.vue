

<template>
  <header>

    <MyNavbar/>
    <MyHome/>
    <MyAbout id="aboutId"/>
    <MyServices id="servicesId"/>

  </header>
</template>

<script lang="ts">

  import MyNavbar from './components/MyNavbar.vue'
  import MyHome from './components/MyHome.vue'
  import MyAbout from './components/MyAbout.vue';
  import MyServices from './components/MyServices.vue';

  export default{

    components:{
      MyNavbar,
      MyHome,
      MyAbout,
      MyServices
    }
  }

</script>