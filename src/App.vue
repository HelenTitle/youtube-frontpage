<script setup>
import AppGrid from './components/AppGrid.vue';
import AppHeader from './components/AppHeader.vue';
import AppBudge from './components/AppBudge.vue';
</script>

<template>
	<div class="page_container">
		<AppHeader />

		<div class="flex">
			<aside>
				<ul>
					<li>1</li>
					<li>2</li>
					<li>3</li>
					<li>4</li>
					<li>5</li>
				</ul>
			</aside>
			<div>
				<div class="badge__container">
					<AppBudge v-for="i in 20">Comedy {{ i }}</AppBudge>
				</div>
				<AppGrid />
			</div>
		</div>
	</div>
</template>

<style scoped>
.badge__container {
	display: flex;
	gap: 14px;
	padding: 0.5rem 1rem;
	position: sticky;
	top: 78px;
	z-index: 1;
	background-color: rgba(FF, FF, FF 0.9);
	overflow-x: auto;
}

.page_container {
	display: grid;
	grid-template-rows: auto 1fr;
}
</style>
