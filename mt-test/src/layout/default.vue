<template>
  <div class="layout-default">
    <el-container>
      <el-header height=''>
        <my-header />
      </el-header>
      <el-main>
        <router-view></router-view>
      </el-main>
      <el-footer>
        <my-footer />
      </el-footer height=''>
    </el-container>
  </div>
</template>

<script>
import myHeader from '@/components/header/index.vue'
import myFooter from '@/components/footer/index.vue'
export default {
  components: {
    myHeader,
    myFooter
  }
}
</script>

<style lang="scss">
   @import '@/assets/css/public/layout.scss'
</style>
