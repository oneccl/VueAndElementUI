<template>
  <div class="page-home">
    <h2>{{ msg }}</h2>
  </div>
</template>

<!--template(模板)标签：其html内容在页面中不会显示，默认设置了display:none属性-->

<script>

// 暴露一个组件，以让其它组件引入(方便外部读取以及访问)
export default {
  name: "Home",
  data() {
    return {
      msg: '这是Home页面!'
    }
  }
}

</script>