<template>
  <div class="hello">
    <iframe
      :src="youtobeURL"
      frameborder="0"
      allow="autoplay;encrypted-media"
      allowfullscreen
      style="width:100%;height:200px;"
    ></iframe>
    <input v-model="youtobeURL" />
    <div v-html="urlurl"></div>
    <input v-model="urlurl" />
  </div>
</template>

<script>
export default {
  name: 'EditPage',
  data () {
    return {
      youtobeURL: '',
      urlurl: ''
    }
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
