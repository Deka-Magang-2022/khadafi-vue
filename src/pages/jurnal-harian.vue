<script setup lang="ts">
import Jurnal from "@/assets/Jurnal.md";
	useHead({
		title: 'Jurnal Harian',
	});


	


</script>

<template>
	<div>

	<div class="prose border border-black rounded-md p-10">
		<Jurnal />
	</div>
	


	

		<router-link
			:to="{ name: 'home' }"
			class="
				mt-5
				hover:text-gray-200
				dark:hover:text-gray-500
				hover:underline
			"
			>{{ $t('pages.home') }}</router-link
		>
	</div>
</template>

<style scoped></style>

<route lang="yaml">
name: jurnal-harian
</route>
