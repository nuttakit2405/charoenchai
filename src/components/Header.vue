<template>
  <div class="">
      <div class="column">
        <div class="level">
          <router-link :to="{name: 'Home'}">
            <div class="level-left">
                <img src="https://uppic.cc/d/5neC" alt="" />
                <span style="margin-left: 5px"><p class="title is-4">Charoenchai</p></span>
            </div>
          </router-link>
            <div class="level-right">
              <router-link :to="{name: 'Login'}">
                <button class="button is-light">Login</button>
              </router-link>
            </div>
        </div><hr/>
      </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
