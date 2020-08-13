<template>
	<div>
		<label for="r1">修改颜色</label>
		<input type="checkbox" v-model="use" id="r1">
		<br><br>
		<div v-bind:class="{'class1':use}">
			<h1>{{ msg }}</h1>
		</div>
	</div>
</template>

<script>
	export default {
		name: 'hello',
		data() {
			return {
				msg: "hello world!"
			}
		}
	}

</script>
