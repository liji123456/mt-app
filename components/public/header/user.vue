<template>
<div class="m-user">
  <template v-if="user">
    歡迎您， <span class="username">{{user}}</span>
    [<nuxt-link to="/exit">退出</nuxt-link> ]
  </template>
  <template v-else="!user">
    <nuxt-link to="/login" class="login">立即登陸</nuxt-link>
    <nuxt-link to="/register" class="register">注冊</nuxt-link>
  </template>
</div>
</template>
<script>
export default {
  data() {
    return {
      user: ''
    }
  }
}
</script>
