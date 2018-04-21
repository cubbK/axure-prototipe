<template>
  <md-toolbar class="md-accent" md-elevation="1">
    <router-link to="/" class="logo">
      <h3 class="md-title" >CATS.IO</h3>
    </router-link>

      <router-link to="about">
        <md-button class="md-primary">About</md-button>
      </router-link>

    </md-toolbar>
</template>

<script>
export default {
  name: 'HeaderComp',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
 .logo {
   flex: 1;
   color: inherit;
 }
</style>
