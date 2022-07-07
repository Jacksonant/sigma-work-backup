<script context="module">
	import HOME from './home.json';

	export async function load({ params }) {
		let slug = params.feature;

		const pageRoot = HOME.find((p) => p.page === 'index');
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
	import Index_Nav from '../components/Index/Index_Nav.svelte'
  import Index_Section1 from '../components/Index/Index_Section1.svelte'
  import Index_Section2 from '../components/Index/Index_Section2.svelte'
  import Index_Section3 from '../components/Index/Index_Section3.svelte'
  import Index_Section4 from '../components/Index/Index_Section4.svelte'
  import Index_Section5 from '../components/Index/Index_Section5.svelte'
  import Index_Section6 from '../components/Index/Index_Section6.svelte'
  import Index_Section7 from '../components/Index/Index_Section7.svelte'
  import Index_Section8 from '../components/Index/Index_Section8.svelte'
  import Index_Section9 from '../components/Index/Index_Section9.svelte'
  import Index_Footer from '../components/Index/Index_Footer.svelte'

	export let pageComponents;
</script>

<svelte:head>
	<link rel="stylesheet" href="/src/main.css" />
</svelte:head>

{#each pageComponents as elem}
	{#if elem.id === 'Index_Nav'}
		<Index_Nav payload={elem.content} />
  {:else if elem.id === 'Index_Section1'}
		<Index_Section1 payload={elem.content} />
  {:else if elem.id === 'Index_Section2'}
		<Index_Section2 payload={elem.content} />
  {:else if elem.id === 'Index_Section3'}
		<Index_Section3 payload={elem.content} />
  {:else if elem.id === 'Index_Section4'}
		<Index_Section4 payload={elem.content} />
  {:else if elem.id === 'Index_Section5'}
		<Index_Section5 payload={elem.content} />
  {:else if elem.id === 'Index_Section6'}
		<Index_Section6 payload={elem.content} />
  {:else if elem.id === 'Index_Section7'}
		<Index_Section7 payload={elem.content} />
  {:else if elem.id === 'Index_Section8'}
		<Index_Section8 payload={elem.content} />
  {:else if elem.id === 'Index_Section9'}
		<Index_Section9 payload={elem.content} />
  {:else if elem.id === 'Index_Footer'}
		<Index_Footer payload={elem.content} />
	{:else}
		no such component
	{/if}
{/each}
