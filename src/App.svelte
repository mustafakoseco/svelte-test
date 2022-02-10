<script>
	let name = 'for yazilim'
	let src = 'img/for.png'
	let alt = 'for logo'
</script>

<main>
	<h1>Merhaba {name}!</h1>
	<p>Görüşme 10/02/2022 13:30' da gerçekleşecektir.</p>
	<img {src} {alt} >
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ec112e;
		text-transform: uppercase;
		font-size: 4rem;
		font-weight: 100;
	}

	p {
		font-size:2rem;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>