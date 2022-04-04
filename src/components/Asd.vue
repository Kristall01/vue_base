<template>
	<form @submit="asd">
		<input type="submit">
	</form>
</template>

<script>
	export default {
		methods: {
			asd(e) {
				e.preventDefault();
				console.log("hello");
			}
		}
	}
</script>