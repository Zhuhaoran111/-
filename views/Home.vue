<template>
<div>
  <el-container style="height:400px">
  <el-aside width="auto">
    <CommonAside></CommonAside>
  </el-aside>
  <el-container>
    <el-header>Header</el-header>
    <el-main>Main</el-main>
  </el-container>
</el-container>
</div>
</template>

<script>

import CommonAside from '../src/components/CommonAside.vue'
export default {
     name:'Home',
     components:{
      CommonAside,
     },
     data(){
        return{

        }
     }
   
}
</script>

<style lang="less" scoped>
.el-header{
   background-color: #333;

}
.el-main{
   padding-top:0;
}

</style>