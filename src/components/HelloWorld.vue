<template>
	<v-container>
		<v-flex
			xs12
			align-center
			justify-center
			layout
			text-xs-center
			ma-0
			pa-0
		>
			<v-avatar
				size="128"
				color="grey lighten-4"
			>
				<img src="../assets/avatar.jpg" alt="Emiliano Díaz">
			</v-avatar>
		</v-flex>
		<v-flex
			xs12
			align-center
			justify-center
			layout
			text-xs-center
			ma-0
			mt-2
			pa-0
		>
			<h1>{{ msg }}</h1>
		</v-flex>
	</v-container>
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
