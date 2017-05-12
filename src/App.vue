<template>
	<ol>
        <li v-for='item in groceryList' v-html="item.text"></li>
    </ol> 
</template>
<script>
export default {
	data: function(){
		return {
			groceryList: [{
	            text: '<p style="color:red">蔬菜</p>'
	        }, {
	            text: '水果'
	        }, {
	            text: '其他'
	        }]
		}
	}
}
</script>
<style></style>