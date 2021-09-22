<template>
	<button class="">
		<slot>按钮</slot>
	</button>
</template>

<script>
	/**
	 * YButton 按钮组件
	 * @description 这是一个自定义的按钮
	 * @tutorial https://www.28yanyu.cn
	 */
	export default {
		name:"y-button",
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss" scoped>
	// 引入公共样式文件
	@import "../../style/common.scss";
	// 自定义的样式库
	@import "./button.scss";
</style>
