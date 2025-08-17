

<template>

    <MyNavbar/>
    <MyHome/>
    <MyAbout/>
    <MyServices/>
    <MySkills/>

</template>

<script lang="ts">

  import MyNavbar from './components/MyNavbar.vue'
  import MyHome from './components/MyHome.vue'
  import MyAbout from './components/MyAbout.vue';
  import MyServices from './components/MyServices.vue';
  import MySkills from './components/MySkills.vue';

  export default{

    components:{
      MyNavbar,
      MyHome,
      MyAbout,
      MyServices,
      MySkills
    }
  }

</script>