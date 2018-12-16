<template>
  <el-container>
    <el-header style="height: 40px">
      <my-header/>
    </el-header>
    <el-main>
      <nuxt/>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>
</template>

<script>
  import MyHeader from '../components/public/header'

  export default {
    components: {
      MyHeader
    }
  }
</script>
