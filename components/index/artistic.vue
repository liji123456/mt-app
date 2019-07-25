<template>
<section class="m-istyle">
  <dl>
    <dt>有格調</dt>
    <dd :class="{active:kind==='all'}" kind="all" keyword="景点"> 全部</dd>
    <dd>约会聚餐</dd>
    <dd>约会聚餐</dd>
    <dd>约会聚餐</dd>
    <dd>约会聚餐</dd>
    <dd>约会聚餐</dd>
  </dl>
  <ul class="ibody">
    <li v-for="(item,idx) in list" :key="idx">
      <el-card :body-style="{ padding: '0px' }" shadow="never">
        <img :src="item.img" class="image">
        <ul class="cbody">
          <li class="title">{{item.title}}</li>
          <li class="pos">{{item.pos}}</li>
          <li class="price">{{item.price}}</li>
        </ul>
      </el-card>
    </li>
  </ul>
</section>
</template>
<script>
export default {
  data() {
    return {
      kind: 'all',
      list: [{
        title: '日本豪華午餐',
        pos: '午餐',
        price: '29',
        url: '#abc',
        img: 'http://p0.meituan.net/codeman/00c8bc1c25fbcc6d0651b29a2057a8c1560658.png'
      }, {
        title: '日本豪華午餐',
        pos: '午餐2',
        price: '293',
        url: '#bsbsb',
        img: 'http://p1.meituan.net/codeman/826a5ed09dab49af658c34624d75491861404.jpg'
      }, {
        title: '日本豪華午餐',
        pos: '午餐2',
        price: '294',
        url: '#sjfkajfj',
        img: 'http://p0.meituan.net/codeman/a97baf515235f4c5a2b1323a741e577185048.jpg'
      }, {
        title: '日本豪華午餐',
        pos: '午餐2',
        price: '292',
        url: '#sjfkajfja',
        img: 'http://p0.meituan.net/codeman/33ff80dc00f832d697f3e20fc030799560495.jpg'
      }, {
        title: '日本豪華午餐',
        pos: '午餐',
        price: '291',
        url: '#kjljj',
        img: 'http://p1.meituan.net/codeman/bb0abb3435a60c44d87e90ed4237b61039329.jpg'
      }, {
        title: '日本豪華午餐',
        pos: '午餐',
        price: '291',
        url: '#kjljj',
        img: 'http://p1.meituan.net/codeman/bb0abb3435a60c44d87e90ed4237b61039329.jpg'
      }]
    }
  }
}
</script>
<style lang="scss">
@import "@/assets/css/index/artistic.scss"
</style>
