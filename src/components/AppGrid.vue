<script setup>
import AppVideo from './AppVideo.vue';
</script>

<template>
	<div
		class="p-4 grid gap-5 grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4"
	>
		<AppVideo v-for="i in 10" />
	</div>
</template>
