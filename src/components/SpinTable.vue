<template>
	<div>
		<span class="centered half-screen z-50">
			<span class="animate-ping absolute h-full w-full rounded-full bg-gray-500 opacity-50"></span>
		</span>
	</div>
</template>

<script>
export default {
	name: 'spinTable',
}
</script>

<style>
div.masked {
	position: relative;
}

div.masked:before {
	position: absolute;
	content: '';
	width: 100%;
	height: 100%;
	background-color: rgb(114, 110, 110, 0.7);
}

span.ping {
	background-color: rgb(143, 174, 144);
}
</style>
