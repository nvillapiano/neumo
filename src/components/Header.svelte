<header>
  <h1>
    <h1>Hello {name}!</h1>
  </h1>
</header>

<script>
	export let name;
</script>

<style type="text/scss">
  $color: yellow;

	h1 {
		color: $color;
		/* text-transform: uppercase; */
		font-size: 4em;
		font-weight: 100;
	}
</style>