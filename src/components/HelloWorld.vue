<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      This is application was written in Vue.js By <strong>Brian Palazzola</strong><br>
      any questions please review documents at 
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">Vue Documentation</a>.
    </p>
    <h3>Contact Me</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">Call</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">Email</a></li>
    </ul>
    <h3>Links to Social Media</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Links to Projects</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">Awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
  font-size: 24px;
  font-family: 'Tahoma', Geneva, Verdana, sans-serif;
  background-color: aqua;

}
ul {
  list-style-type: none;
  padding: 0;
  background-color: rgb(228, 43, 43);
  height: 35px;
  text-align: center;
}
li {
  display: inline-block;
  margin: 0 15px;
  padding: 5px;
  
}
a {
  color: #74ebb5;
  font-family: 'Tahoma', Geneva, Verdana, sans-serif;
}
p  {
  font-family: 'Tahoma', Geneva, Verdana, sans-serif;
  background-color: rgba(60, 126, 126, 0.699);
}
img {
  width: 300; 
  height: 600;
}
</style>
