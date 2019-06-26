<!-- 用于显示页面的标题（之后我们用它测试下继承于ListPageAbstract.vue的组件如何重写css的问题） -->
<template>
  <div class="title">{{ title }}</div>
</template>
<script type="text/javascript">
export default {
  props: ['title']
}
</script>