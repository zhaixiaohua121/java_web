<template>
  <div >
<!--    <h1>{{message}}</h1>-->
<emp-view></emp-view>
  </div>
</template>
<script>
  import EmpView from "@/views/tlias/EmpView.vue";

  export default {
      components: {EmpView},
      data(){
          return{
              message:"hello world"
          }
      },
      methods:{
      }
  }
</script>
<style>

</style>
