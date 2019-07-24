<template>
<div class="my-header">
  <el-row>
    <el-col>
      <topbar />
    </el-col>
  </el-row>
  <el-row>
    <el-col>
    </el-col>
  </el-row>
</div>
</template>
<script>
import topbar from './topbar.vue'
import searchBar from './searchbar.vue'
export default {
  components: {
    topbar,
    searchBar
  }
}
</script>
  <style lang="sass">
    @import "@/assets/css/public/layout.scss";
    @import "@/assets/css/public/header/index.scss";
  </style>
