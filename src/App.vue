<template>
  <div id="app">
    <nav>
      <NavBar/>
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    </nav>
    <b-container>
      <router-view/>
    </b-container>
  </div>
</template>
<script>
  import NavBar from '@/components/NavBar'
  export default{
    components : {
      NavBar
    }
  }

</script>

<style lang="scss">
</style>
