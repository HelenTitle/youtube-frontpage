<template>
	<div>
		<div class="relative">
			<img
				src="https://picsum.photos/400/200"
				class="object-cover aspect-video"
			/>
			<span class="video__time">14:10</span>
		</div>

		<div class="flex gap-3 items-start mt-2">
			<img src="https://picsum.photos/36/36" class="rounded-full" alt="" />
			<div class="grow">
				<h4 class="line-clamp-2 video__title">
					Playing Fortnite all day lorem Playing Fortnite all day lorem Playing
					Fortnite all day loremPlaying Fortnite all day lorem
				</h4>
				<div class="text-sm text-grey-500">
					<div>evtratv</div>
					<div>2,1M views 2 days ago</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>
.video__title {
	font-size: 16px;
}

.video__time {
	background-color: black;
	color: white;
	padding: 5px;
	font-size: 14px;
	position: absolute;
	bottom: 0px;
	right: 0px;
}
</style>
