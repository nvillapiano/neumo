<main>
	<Header name={'Nico'}></Header>
	<p>
    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Fuga necessitatibus nemo aliquid. Illum, a ratione fuga officia quasi, molestias similique corporis eum vero error reprehenderit eveniet veritatis magnam doloremque est.
  </p>
</main>

<script>
	import Header from './components/Header.svelte';
</script>

<style type="text/scss">
	@import "./styles/index.scss";
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;

		p {
			height: 300px;
			width: 300px;
			padding: 20px;
			margin: 40px auto;
			@extend %shadowBasic;
		}

	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>