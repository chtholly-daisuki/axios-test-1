<script setup>

</script>

<template scoped>
    
    <div class="oricon">
        欢迎使用学生论坛系统
        <br></br>
        制作者：chtholly_daisuki
        <br></br>
        <div>
          <router-link :to="{path:'login'}" class="btn">开始登陆</router-link>
        </div>
        
    </div>
</template>

<style scoped>
.oricon{
  display:flex;
  align-items:center;
  justify-content:center;
  max-width: 800px;
  margin: 2rem auto;
  padding: 0 1rem;
}
.btn {
  display:flex;
  padding: 8px 16px;
  background-color: #42b983;
  color: white;
  border: none;
  border-radius: 4px;
  /*cursor: pointer;*/
  text-decoration: none; /* 去除链接默认下划线 */
}
</style>