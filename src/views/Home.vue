<template>
	<div class="home align-center justify-center text-xs-center">
		<HelloWorld msg="Welcome to my Site."/>
	</div>
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
