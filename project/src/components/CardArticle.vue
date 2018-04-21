<template>
  <md-card class="card">
      <md-card-media>
        <img v-bind:src="article.img" alt="People">
      </md-card-media>

      <md-card-header>
        <router-link v-bind:to="`/article/${article.title}`" class="logo">
         <div class="md-title">{{ article.title }}</div>
        </router-link>

        <div class="md-subhead">Subtitle here</div>
      </md-card-header>

      <md-card-actions>
        <md-button>Action</md-button>
        <md-button>Action</md-button>
      </md-card-actions>

      <md-card-content>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Optio itaque ea, nostrum odio. Dolores, sed accusantium quasi non, voluptas eius illo quas, saepe voluptate pariatur in deleniti minus sint. Excepturi.
      </md-card-content>
    </md-card>

</template>

<script>
export default {
  name: 'Article',
  props: ['article'],
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .card {
    margin: 30px 0;
  }
</style>
