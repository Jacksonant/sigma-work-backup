<script context="module">
	import HOME from './home.json';

	export async function load({ params }) {
		let slug = params.feature;

		const pageRoot = HOME.find((p) => p.page === 'employers');
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
	import Employers_Nav from '../components/Employers/Employers_Nav.svelte';
	import Employers_Section1 from '../components/Employers/Employers_Section1.svelte';
	import Employers_Section2 from '../components/Employers/Employers_Section2.svelte';
	import Employers_Section3 from '../components/Employers/Employers_Section3.svelte';
	import Employers_Section4 from '../components/Employers/Employers_Section4.svelte';
	import Employers_Section5 from '../components/Employers/Employers_Section5.svelte';
	import Employers_Section6 from '../components/Employers/Employers_Section6.svelte';
	import Employers_Footer from '../components/Employers/Employers_Footer.svelte';


	export let pageComponents;
</script>

<svelte:head>
	<link rel="stylesheet" href="/src/main.css" />
</svelte:head>

{#each pageComponents as elem}
	{#if elem.id === 'Employers_Nav'}
		<Employers_Nav payload={elem.content} />
  {:else if elem.id === 'Employers_Section1'}
		<Employers_Section1 payload={elem.content} />
  {:else if elem.id === 'Employers_Section2'}
		<Employers_Section2 payload={elem.content} />
  {:else if elem.id === 'Employers_Section3'}
		<Employers_Section3 payload={elem.content} />
  {:else if elem.id === 'Employers_Section4'}
		<Employers_Section4 payload={elem.content} />
  {:else if elem.id === 'Employers_Section5'}
		<Employers_Section5 payload={elem.content} />
  {:else if elem.id === 'Employers_Section6'}
		<Employers_Section6 payload={elem.content} />
  {:else if elem.id === 'Employers_Footer'}
		<Employers_Footer payload={elem.content} />

	{:else}
		no such component
	{/if}
{/each}
