

<template>

    <MyNavbar/>
    <MyHome/>
    <MyAbout/>
    <MySkills/>
    <MyServices/>
    <MyContact/>

</template>

<script lang="ts">

  import MyNavbar from './components/MyNavbar.vue'
  import MyHome from './components/MyHome.vue'
  import MyAbout from './components/MyAbout.vue';
  import MyServices from './components/MyServices.vue';
  import MySkills from './components/MySkills.vue';
  import MyContact from './components/MyContact.vue';

  export default{

    components:{
      MyNavbar,
      MyHome,
      MyAbout,
      MyServices,
      MySkills,
      MyContact
    }
  }

</script>