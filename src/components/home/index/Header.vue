<template>
  <header class="header">
  <div class="content">
    <div class="search">
        <input type="text" placeholder="请输入搜索内容" />
    </div>
        <div class="banner">
            <!--<img src="static/img/banner.png"/>-->
        </div>
  </div>
  </header>
</template>

<script>
export default {
    name: 'home-header'
}
</script>

<style scoped>
.header{
    width: 100%;
    height: 80px;
    background-image: linear-gradient(90deg,#0af,#0085ff);
}


</style>
