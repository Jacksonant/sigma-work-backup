<script context="module">
	import HOME from './home.json';

	export async function load({ params }) {
		let slug = params.feature;

		const pageRoot = HOME.find((p) => p.page === 'talents');
		console.log(pageRoot);

		const pageComponents = pageRoot?.components;
		console.log('features', pageComponents);
		return {
			props: {
				pageComponents
			}
		};
	}
</script>

<script>
	import Talents_Nav from '../components/Talents/Talents_Nav.svelte';
	import Talents_Section1 from '../components/Talents/Talents_Section1.svelte';
	import Talents_Section2 from '../components/Talents/Talents_Section2.svelte';
	import Talents_Section3 from '../components/Talents/Talents_Section3.svelte';
	import Talents_Section4 from '../components/Talents/Talents_Section4.svelte';
	import Talents_Section5 from '../components/Talents/Talents_Section5.svelte';
	import Talents_Footer from '../components/Talents/Talents_Footer.svelte';

	export let pageComponents;
</script>

<svelte:head>
	<link rel="stylesheet" href="/src/main.css" />
</svelte:head>

{#each pageComponents as elem}
	{#if elem.id === 'Talents_Nav'}
		<Talents_Nav payload={elem.content} />
  {:else if elem.id === 'Talents_Section1'}
		<Talents_Section1 payload={elem.content} />
  {:else if elem.id === 'Talents_Section2'}
		<Talents_Section2 payload={elem.content} />
  {:else if elem.id === 'Talents_Section3'}
		<Talents_Section3 payload={elem.content} />
  {:else if elem.id === 'Talents_Section4'}
		<Talents_Section4 payload={elem.content} />
  {:else if elem.id === 'Talents_Section5'}
		<Talents_Section5 payload={elem.content} />
  {:else if elem.id === 'Talents_Footer'}
		<Talents_Footer payload={elem.content} />
	{:else}
		no such component
	{/if}
{/each}


