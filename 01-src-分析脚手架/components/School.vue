<template>
    <div>
        <h1>学校地址：{{schoolName}}</h1>
        <h1>学校名字：{{schoolAdress}}</h1>
        <button @click="showName">点我提示校名</button>
    </div>
</template>

<script>
export default {
    name:'SchoolMessage',
    data() {
        return {
            schoolName:'杭州电子科技大学',
            schoolAdress:'杭州下沙'
        }
    },
    methods: {
        showName(){
            alert(this.schoolName)
        }
    },
    
}
</script>




