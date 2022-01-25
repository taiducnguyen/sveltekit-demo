<script context="module" lang="ts">
	export const prerender = true;
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<main class="container">
	<h1 class="title">SvelteKit - Measure page quality</h1>

	<p class="description">
		Test your pages in a lab environment powered by PageSpeed Insights. Then get tips and
		recommendations to improve your user experience. For field performance, see the <a
			target="_blank"
			href="https://pagespeed.web.dev/?utm_source=psi&utm_medium=redirect">PageSpeed Insights</a
		> tool.
	</p>

	<img src="/testing.jpg" width={400} height={400} alt="Testing"/>
</main>

<style>
	.container {
		min-height: 100vh;
		padding: 0 0.5rem;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	main {
		padding: 5rem 0;
		flex: 1;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.title {
		margin: 0;
		line-height: 1.15;
		font-size: 4rem;
	}

	.title,
	.description {
		text-align: center;
	}

	.description {
		line-height: 1.5;
		font-size: 1.5rem;
	}
</style>
