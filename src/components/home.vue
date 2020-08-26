<template>
  <el-container>
    <el-header style="background-color: pink;height: 139px;width:1519px;">
      Header
    </el-header>
    <el-main style="background-color: blue;width:1519px;padding:0px;"><!--height: 2558px;-->
      <div id="slideshow" style="height: 360px;width: 1519px;background-color: #42b983;"><!--轮播图-->

      </div>
      <div id="courseType" style="height: 166px;width:1519px;background-color: #20a0ff;"><!--课程类别-->

      </div>
      <div id="teacher" style="height: 317px;width: 1519px;background-color: palegreen;"><!--推荐讲师-->

      </div>
      <div id="course" style="height: 311px;width: 1519px;background-color: papayawhip;"><!--微课程，课程特色-->

      </div>
      <div id="hobby"style="height: 60px;width: 1519px;background-color:powderblue;"><!--兴趣推荐-->

      </div>
      <div id="hobbyCourse">
        <div id="hobbyCourse1" style="width: 1205px;height: 222px;background-color: #409EFF;margin: 0 auto;">

        </div><!--推荐课程1-->
        <div id="hobbyCourse2" style="width: 1205px;height: 222px;background-color:lavender;margin: 0 auto;">

        </div><!--推荐课程2-->
      </div>
    </el-main>
    <el-footer style="background-color: red;height: 183px;width: 1519px;">
      Footer
    </el-footer>
  </el-container>
</template>

<script>
  export default {
    name: 'home'
  }
</script>

<style scoped>
  body, textarea, select, input {
    font-family: "Arial","Hiragino Sans GB", \5fae\8f6f\96c5\9ed1, "Helvetica", "sans-serif";
    font-size: 14px;
    line-height: 21px;
    color: #343d42;
    outline: none;
    border: 0;
  }
</style>
