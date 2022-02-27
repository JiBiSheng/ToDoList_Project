<template>
  <div>
      <h1 ref="title">欢迎你</h1>
      <Student ref="sch"/>
      <button @click="showDom">点我</button>
  </div>
  
</template>

<script>
import Student from './components/Student.vue'
export default {
    name:'App',
    components:{
        Student
    },
    methods:{
        showDom(){
            console.log(this.$refs);
        }
    }
}
</script>

<style>

</style>