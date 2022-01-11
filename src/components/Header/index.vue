<template>
  <div>
    <div class="header">
      <div class="nav_left">
        <ul>
          <li><a href="#">关于我们</a></li>
          <li><a href="#">反馈</a></li>
          <li><a href="#">侵权投诉</a></li>
        </ul>
      </div>
      <div class="nav_right">
        <div class="weather">
          <span>桂林</span>
          <img src="./images/weather.png" class="tu">
          <span>阴 14°C</span>
          <span> 良</span>
        </div>
        <img src="./images/add.png" class="add">
        <span class="publish">发布作品</span>
        <span class="login">登录</span>
      </div>
    </div>
    <div class="container">
      <a href="#"><h2 class="title">摘新官网</h2></a>
      <div class="search">
        <input type="text" placeholder="请输入要搜索的内容">
      </div>
      <div class="hot-search">
        <img src="./images/hot-search.png" alt="">
        <span>热搜：</span>
        <span><a href="#">社科院预测世界经济</a></span>
        <span><a href="#">英特尔发布声明</a></span>
        <span><a href="#">北交所首只新股申购</a></span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped>
*{
  margin: 0;
  padding: 0;
}
a{
  font-size: 16px;
  text-decoration: none;
}
.header{
  width: 100%;
  height: 45px;
  background-color: #000;
  color: #fff;
  text-align: center;
  position:fixed;
  top: 0;
}
.header .nav_left{
  float: left;
  height: 100%;
  display: inline-block;
  color: #fff;
}
.header .nav_left li{
  float: left;
  margin-left: 10px;
  padding: 0 15px;
  list-style: none;
  /*background-color: red;*/
  height: 100%;
  line-height: 45px;
  font-size: 14px;
  text-align: center;
  font-size: 16px;
}
.header .nav_left li a{
  font-size: 16px;
  color: #fff;

}
.header .nav_right {
  float: right;

}
.header .nav_right .weather{
  position: relative;
  top:-5px;
  right: 120px;
  display: inline-block;
  /*padding-right: 200px;*/
}
.header .nav_right .weather .tu{
  position: relative;
  top:10px;
  right: 0px;
}
.header .nav_right .add{
  position: relative;
  top: 5px;
  right: 80px;
  display: inline-block;
}
.header .nav_right .publish{
  position: relative;
  top: -5px;
  right: 80px;
}
.header .nav_right .login{
  position: relative;
  top: -5px;
  right: 30px;
  width: 60px;
  height: 30px;
  border-radius: 5px;
  text-align: center;
  display: inline-block;
  line-height: 30px;
  background-color: #ff0000;
}


.container{
  width: 1080px;
  height: 500px;
  color: #fff;
  margin-right: auto;
  margin-left: auto;
  background-color: skyblue;
  text-align: center;
  margin-top: -15px;
}
.container .title{
  position: relative;
  top: 30%;
  left: 3%;
  font-size: 36px;
  color: #fff;
  font-family: "Microsoft YaHei", "宋体", "Segoe UI", "Lucida Grande", Helvetica, Arial, sans-serif, FreeSans, Arimo;
}
.container .hot-search img{
  position: relative;
  top: 5px;
  left: 0px;
}
.container .search{
  width: 100%;
  position: relative;
  top: 240px;
  left: 0;
}
.container .search input{
  width: 500px;
  height: 40px;
  padding-left: 5px;
  margin-left: 10%;
}
.container .hot-search{
  position: relative;
  top: 240px;
  left: 3%;
}
.container .hot-search a{
  color: #fff;
}
.container .hot-search a:hover{
  color: #ff0000;
}



</style>
