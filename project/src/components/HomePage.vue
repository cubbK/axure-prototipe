<template>
  <div class="container">
    <card-article  v-for="article in articles" v-bind:article="article" v-bind:key="article.title"></card-article>
  </div>
</template>

<script>
import CardArticle from './CardArticle'
import data from '../data.json'

export default {
  name: 'HomePage',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      articles: data.articles
    }
  },
  components: {
    CardArticle
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .container{
    margin: 0 auto;
    width: 40%;
  }
</style>
