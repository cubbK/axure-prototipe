<template>
  <card-article img="msg" title="123"></card-article>
</template>

<script>
import CardArticle from './CardArticle'
export default {
  name: 'ArticleComp',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    CardArticle
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
