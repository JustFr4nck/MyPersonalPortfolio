

<template>
  <header>

    <MyNavbar/>
    <MyHome/>

  </header>
</template>

<script lang="ts">
  import MyNavbar from './components/MyNavbar.vue'
  import MyHome from './components/MyHome.vue'

  export default{

    components:{
      MyNavbar,
      MyHome
    }
  }

</script>