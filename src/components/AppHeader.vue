<script setup>
import AppLogo from './AppLogo.vue';
import SearchIcon from '../icons/SearchIcon.vue';
import bellicon from '../icons/bellicon.vue';
import gridicon from '../icons/gridicon.vue';
import Humburgericon from '../icons/Humburgericon.vue';
import Videoicon from '../icons/videoicon.vue';
</script>

<template>
	<header>
		<div class="flex gap-2">
			<button>
				<Humburgericon class="w-6 h-6" />
			</button>
			<AppLogo class="w-24" />
		</div>
		<form action="">
			<input type="text" />
			<button class="form_button">
				<SearchIcon class="w-6 h-6" />
			</button>
		</form>
		<div class="flex gap-2">
			<button>
				<Videoicon class="w-6 h-6" />
			</button>
			<button>
				<gridicon class="w-6 h-6" />
			</button>
			<button>
				<bellicon class="w-6 h-6" />
			</button>
			<img src="https://picsum.photos/100/100" class="w-8 h-8 rounded-full" />
		</div>
	</header>
</template>

<style scoped>
header {
	position: sticky;
	padding: 1rem;
	top: 0px;
	z-index: 1;
	background-color: rgba(255, 255, 255, 0.9);
	display: flex;
	justify-content: space-between;
	align-items: center;
}

form {
	border: 1px solid #ccc;
	display: flex;
}

.form_button {
	background-color: #f0f0f0;
	padding: 10px;
	height: 100%;
}
</style>
