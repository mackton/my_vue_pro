<template>
  <div class="header">
			<div class="search">
				<form action="search.html">
					<input type="hidden" style="display: none;" name="search" id="search" placeholder="输入内容搜索" />
					<input type="text" name="search" id="search" placeholder="输入内容搜索" />
				</form>
			</div>
	</div>
</template>

<script>
// import foot from './components/foot'
export default {
  // components: { foot }
}
</script>

<style>
.header{
  position: fixed;
  z-index: 1;
  top: 500px;
  width: 100%;
  height: 90px;
  padding-top: 10px;
  padding-bottom: 10px;
  background-color: #efefef;
}
.search{
  background: url(../assets/search.png) no-repeat 20px 15px;
  border-radius: 50px;
  width: 90%;
  height: 70px;
  margin: auto;
  background-color: #fff;
  overflow: hidden;
}
img{margin: 15px;float: left;}
input{
  display: inline;
  width: 100%;
  height: 70px;
  border: none;
  padding: 0;
  margin-left: 70px;
  font-size: 2em;}
</style>
