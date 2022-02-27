<template>
  <div class="school">
    <h1>学校名称:{{name}}</h1>
    <h2>学校地址：{{address}}</h2>
  </div>
</template>

<script>
export default {
    name:'SchoolName',
    data() {
        return {
            name:'杭州电子科技大学',
            address:'杭州下沙'
        }
    },
};
</script>

<style>
.school{
    background-color: gray;
}
</style>