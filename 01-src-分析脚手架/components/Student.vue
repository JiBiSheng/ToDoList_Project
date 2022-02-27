<template>
  <div>
        <h1>学生姓名：{{studentName}}</h1>
        <h1>学生年龄：{{studentAge}}</h1>   
        <button @click="showName">点我提示学生姓名</button>     
    </div>
</template>

<script>
export default {
    name:'StudentMessage',
     data() {
        return {
            studentName:'季毕胜',
            studentAge:'18'
        }
    },
    methods: {
        showName(){
            alert(this.studentName);
        }
    },
}
</script>
