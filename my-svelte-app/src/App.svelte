<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<h2>Hola Irina</h2>

	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #99ff00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	h2 {
		font-size: 60px;
		color: #fff;
		text-align: center;
		text-shadow: 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #ff00de, 0 0 70px #ff00de,
			0 0 80px #ff00de, 0 0 100px #ff00de, 0 0 150px #ff00de;
}


	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>