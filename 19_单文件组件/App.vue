<!--
 * @Description: 
 * @Version: 2.0
 * @Autor: Lai
 * @Date: 2023-08-07 14:01:40
 * @LastEditors: Lai
 * @LastEditTime: 2023-08-07 14:11:41
-->
<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
// 引入组件
// import School from './School'
import School from './School.vue'
import School from './School.vue'
// import Student from './Student'
export default {
    name:`App`,
    components:{
        School,
        Student
    }
}
</script>

<style>

</style>