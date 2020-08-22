<template>
	<h1>{{ msg }}</h1>
	<button @click="count++">count is: {{ count }}</button>
	<p>
		Edit
		<code>components/HelloWorld.vue</code> to test hot module replacement.
	</p>
</template>

<script lang="ts">
import { VNode } from 'vue';
import { IconifyIcon } from '@iconify/types';

export default {
	name: 'HelloWorld',
	props: {
		msg: String,
	},
	data() {
		return {
			count: 0,
		};
	},
};
</script>
