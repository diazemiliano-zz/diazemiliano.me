<template>
	<v-layout layout row wrap align-center justify-center>
		<HelloWorld msg="Welcome to my Site."/>
	</v-layout>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
