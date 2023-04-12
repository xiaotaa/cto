<template>
  <div>
    <img src="@/assets/logo.png">
  <div id="">
    <div id="">账号：<input type="text" v-model="account"></div>
    <div id="">密码：<input type="password" name="" id="" v-model="passwprd"></div>
    <input type="button" value="登录" @click="login">
  </div>
  </div>
</template>
<script>
export default {
  data(){
   return ({
      account:"",
    password:""
   })
  },
  methods:{
    login(){
      if(!this.account){
        alert("用户名不能为空，请输入用户名")
      }
       if(!this.password){
         alert("密码不能为空，请输入密码")
       }
    }
  }
}
</script>

<style>

</style>

