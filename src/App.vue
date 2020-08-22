<template>
	<img alt="Vue logo" src="./assets/logo.png" />
	<HelloWorld msg="Hello Vue 3.0 + Vite" />
</template>

<script>
import { foo } from './test';
import HelloWorld from './components/HelloWorld.vue';

foo();

export default {
	name: 'App',
	components: {
		HelloWorld,
	},
};
</script>
