<template>
  <div class="hello-component">
		Hello world,Vue and webpack
	</div>
</template>

<script>
export default {
 
}
</script>
<!--通过 scoped修饰符 增加css的作用域为当前组件-->
<style scoped>
	.hello-component{
		font-size: 50px;
	}
</style>
