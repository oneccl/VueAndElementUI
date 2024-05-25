<template>
  <div class="page-app">
    <h2>{{ msg }}</h2>
    <!--插入组件：引入的组件标签，和import中的名称保持一致-->
    <Home></Home>
  </div>
</template>

<script>

// vue项目必须安装node

// 引入Home组件
import Home from "./home";

// 暴露一个组件，方便外部读取以及访问
export default {
  name: "App",
  // 注册引入的组件
  components: {Home},
  data() {
    return {
      msg: '这是App页面!'
    }
  }
}

</script>