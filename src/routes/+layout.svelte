<script lang="ts">
	import '../app.css';
	import favicon from '$lib/assets/favicon.svg';
	import Header from "$lib/components/header.svelte";
	import Navbar from '$lib/components/navbar.svelte';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
</svelte:head>

<div class="min-h-screen min-w-screen bg-pink-900">
	<Header/>
	<Navbar/>
	{@render children?.()}
</div>