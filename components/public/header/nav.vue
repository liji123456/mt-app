<template>
<div class="m-nav">
  <ul class="nav">
    <li class="list">
      <nuxt-link to="/order">我的美團</nuxt-link>
      <dl>
        <dd>
          <nuxt-link to="/order">我的訂單</nuxt-link>
        </dd>
        <dd>
          <nuxt-link to="/order">我的訂單</nuxt-link>
        </dd>
        <dd>
          <nuxt-link to="/order">我的訂單</nuxt-link>
        </dd>
        <dd>
          <nuxt-link to="/order">我的訂單</nuxt-link>
        </dd>
      </dl>
    </li>
    <li>
      <nuxt-link to="/order">我的美團</nuxt-link>
    </li>
    <li class="list bd">
      <nuxt-link to="center">我的美團</nuxt-link>
    </li>
    <li class="list site">
      <nuxt-link to="/site">我的美團</nuxt-link>
    </li>
  </ul>
</div>
</template>
<script>
    export default{}
</script>
  <style lang="sass">
    @import "@/assets/css/public/layout.scss";
    @import "@/assets/css/public/header/index.scss";
  </style>
