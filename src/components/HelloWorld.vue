<template>
	<div class="text-xs-center">
		<v-flex
			xs12
			ma-0
			pa-0
		>
			<h2 class="subheading">{{ msg }}</h2>
		</v-flex>
		<v-flex
			xs12
			ma-0
			pa-0
		>
			<h1 class="headline">I'm a Software Developer</h1>
		</v-flex>
		<v-flex
			xs12
			ma-0
			mt-4
			pa-0
		>
			<v-avatar
				size="128"
				color="grey lighten-4"
			>
				<img class="elevation-7" src="../assets/avatar.jpg" alt="Emiliano Díaz">
			</v-avatar>
		</v-flex>
	</div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
