<template>
  <div class="footer">
			<ul>
				<li><p><img src="img/首页1.png"/></p><p>首页</p></li>
				<li><a href="classify.html"><p><img src="img/分类.png"/></p><p>分类</p></a></li>
				<li><a href="basket.html"><p><img src="img/购物车.png"/></p><p>购物车</p></a></li>
				<li><a href="mine.html"><p><img src="img/我的.png"/></p><p>我的</p></a></li>
			</ul>
	</div>
</template>

<script>
    export default{
      methods:{
        back:function(){
          this.$router.go(-1)
        }
      }
    }
</script>
