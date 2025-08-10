

<template>
  <header>

    <MyNavbar/>
    <MyHome/>
    <MyAbout id="aboutId"/>

  </header>
</template>

<script lang="ts">

  import MyNavbar from './components/MyNavbar.vue'
  import MyHome from './components/MyHome.vue'
  import MyAbout from './components/MyAbout.vue';

  export default{

    components:{
      MyNavbar,
      MyHome,
      MyAbout
    }
  }

</script>