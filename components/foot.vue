<template>
  <div class="footer">
    <!-- <router-link to="/home">www<router-link> -->
			<ul>
				<li><a><p><img :src="index"/></p><p>首页</p></a></li>
				<li><a><p><img :src="classify"/></p><p>分类</p></a></li>
				<li><a><p><img :src="car"/></p><p>购物车</p></a></li>
				<li><a><p><img :src="mine"/></p><p>我的</p></a></li>
			</ul>
		</div>
</template>

<script>
export default {
  data () {
    return {
      index:require('../assets/1.1.png'),
      classify:require('../assets/2.1.png'),
      car:require('../assets/3.1.png'),
      mine:require('../assets/4.1.png'),
    }
  }
}
</script>

<style scoped>
*{
  margin:0px;
  padding:0px;
}
.footer{
	overflow: hidden;
	width: 100%;
	height: 100px;
	border-top: 1px solid #000;
	position: fixed;
	bottom: 0px;
	z-index: 5;
	background-color: #fff;
}
ul{
  width: 100%;
  height: 100px;
  list-style-type: none;
}
li{
  font-size: 25px;
  width: 25%;
  float: left;
  text-align: center;
  padding-top:10px;
}
a{
  color: #333;
}
</style>
