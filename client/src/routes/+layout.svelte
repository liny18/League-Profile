<script>
	import '../app.css';
	import Navbar from '../components/Navbar.svelte';
	import Footer from '../components/Footer.svelte';
</script>

<body>
	<header>
		<nav>
			<Navbar />
		</nav>
	</header>

	<main>
		<slot />
	</main>

	<footer>
		<Footer />
	</footer>
</body>

<style>
	:global(body) {
		margin: 0;
		padding: 0;
		font-family: ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
			'Helvetica Neue', Arial, 'Noto Sans', sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
			'Segoe UI Symbol', 'Noto Color Emoji';
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}
	header,
	footer {
		background-color: #f5f5f5;
	}
	main {
		padding: 2rem;
	}
</style>
