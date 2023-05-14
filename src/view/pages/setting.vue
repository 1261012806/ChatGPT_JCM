<template>
  <div class="setting">
    <el-container>
      <el-header>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <h3>JUN CHEN MO</h3>
          </div>
        </transition>
      </el-header>
      <el-main>
        <transition name="el-zoom-in-top">
          <div v-show="show" class="transition-box">
            <span>
              现已接入OpenAI的Models API、Completions API、Chat API、Audio API、Images API、Files API、Fine-tunes API后续会添加更多有意思的功能满足更多需求。
            </span>
            <div>
              <a href="https://fk.myxinwen.top">OpenAI Key 购买</a>---<a href="https://fk.myxinwen.top">搭建同站点</a>
            </div>
            <div>
              <h3>欢迎使用</h3>
            </div>
            <!--div>
              <img src="https://i.328888.xyz/2023/05/09/iQ8tvv.jpeg" width="300px" height="300px"/>
              <img src="https://i.328888.xyz/2023/05/09/iQNnf3.jpeg" width="300px" height="300px"/>
            </div-->
          </div>
        </transition>
      </el-main>
    </el-container>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      show: false,
    };
  },
  mounted() {
    this.show = true;
  },
};
</script>

<style>
  .transition-box {
    text-align: center;
    margin-top: 5%;
    color: #F2F6FC;
    font-size: 30px;
  }
  h1 {
    color: aliceblue;
    font-size: 80px;
  }
  a {
    text-decoration: none;
    color: #67C23A;
  }
</style>
