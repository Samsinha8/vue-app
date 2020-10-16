<template>
<v-app>
  <div class="hello">
    <input class="searchInput" type="text" placeholder="search" />
  </div>
</v-app>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hello{
  width: 100%;
  height: 75px;
  display: flex;
  align-items: center;
  padding: 0 1%;
  border-bottom: 1px solid #707070;
}
.searchInput{
	width: 200px;
  height: 40px;
	font-size: 18px;
	font-weight: normal;
	color: #333333;
	outline: none;
  border: none;
  background: #cccccc;
  padding: 0 1%;
}
</style>
