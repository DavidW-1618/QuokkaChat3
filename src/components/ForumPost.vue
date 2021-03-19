<template>
	<div class="outer-box">
		<h2>{{name}}</h2>
		<p>{{email}}</p>
		<p>{{comment}}</p>
	</div>
</template>

<script>
export default {
	name: "ForumPost",
	data() {
		return {
			person: {
				id: 254,
				name: "Mike Showerhammer",
				email: "JohnBythewayReferenceMe@gmail.com",
			},
			comment: "Four score and seven years ago our forefathers brought fourth a new criminal quokka prison."
		}
	}
}
</script>

<style scoped>

</style>