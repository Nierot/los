<script lang="ts">
	import '../app.css'
	import { AppBar, AppRail, AppRailAnchor } from '@skeletonlabs/skeleton'
	import { page } from '$app/stores'
	import IconGear from '$lib/components/icons/IconGear.svelte'
	import IconFlowArrow from '$lib/components/icons/IconFlowArrow.svelte'
	import IconBeerBottle from '$lib/components/icons/IconBeerBottle.svelte'
	import IconHelp from '$lib/components/icons/IconHelp.svelte'
</script>

<div class="container h-screen">
	<main class="m-2 ml-4">
		<slot />
	</main>
</div>

<style lang="scss">
</style>
