<template>
	<footer class="absolute bottom-0 left-0 right-0 flex text-center text-sm text-white">
		<div class="flex-1 p-1" style="background:#3333B3;text-align:left;display:inline;">
			{{ $slidev.configs.conference || "Unknown conference" }}
		</div>
		<!-- <div class="flex-1 p-1" style="background:#191959">
			{{ $slidev.configs.author || "Unknown author" }}
		</div> -->
		<div class="flex-1 p-1" style="background:#262686;">
			<img :src=$slidev.configs.socialimg width="30%" style="float: right; vertical-align: middle;">
		</div>
	</footer>
</template>