<template>
  <div class="">
      <div class="column is-4 is-offset-4 box ">
          <p class="title is-4 is-bold">หิวเมื่อไหร่ก็แวะมา</p>
          <input type="text" class="input" placeholder="username" style="margin-bottom: 10px;">
          <input type="text" class="input" placeholder="password" style="margin-bottom: 10px;">
          <button class="button is-success">เข้าสู่ระบบ</button>
          <router-link :to="{name:'Register'}">
          <button class="button is-dark">Register</button></router-link>
      </div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      msg: ''
    }
  }
}
</script>
