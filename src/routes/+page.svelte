<script context="module">
	export const prerender = true;
	import Header from '$lib/header/Header.svelte';
</script>

<svelte:head>
	<title>Frederik Milland</title>
</svelte:head>

<Header />

<section class="hero">
	<img src="Group 58.svg" alt="hero" />
	<div class="hero-text">
		<h3>Hi i'm</h3>
		<h1 class="">
			FREDERIK <br />
			MILLAND
		</h1>
		<h3>
			a UX / UI designer and problem solver 🔧 <br />
			who's creating user friendly design solutions 🏵️<br />
			from beautiful Copenhagen🌇
		</h3>
	</div>
</section>

<section id="portfolio">
	<a sveltekit:prefetch href="/makeimpact">
		<section class="makeimpact">
			<div class="projekt">
				<h4>Fall 2022</h4>
				<h2>The make!mpact app</h2>
				<p>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint minus saepe qui ex facilis
					ipsa dolorem eum, maiores quas maxime? Adipisci cumque magnam fugit ratione excepturi
					ipsum reiciendis nulla beatae soluta exercitationem praesentium dolorum sapiente ea alias
					perferendis a, nemo quas. Architecto aliquid nobis repellat cum mollitia quidem nostrum
					veritatis!
				</p>
			</div>
			<div class="">
				<img src="Mask Group 25.png" alt="m! app" />
			</div>
		</section>
	</a>

	<section class="double-section">
		<a sveltekit:prefetch href="/">
			<div class="nb">
				<div class="projekt">
					<h4>Summer 2022</h4>
					<h2>Nørrebro bryghus</h2>
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint minus saepe qui ex facilis
						ipsa dolorem eum, maiores quas maxime?
					</p>
				</div>
				<div class="">
					<img src="Mask Group 9.png" alt="nørrebro bryhus øl" />
				</div>
			</div>
		</a>

		<a sveltekit:prefetch href="/">
			<div class="vildskud">
				<div class="projekt">
					<h4>Spring 2022</h4>
					<h2>Vildskud festival</h2>
					<p>
						Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint minus saepe qui ex facilis
						ipsa dolorem eum, maiores quas maxime?
					</p>
				</div>
				<div class="">
					<img class="w-56" src="Group 63.svg" alt="vildskud logo" />
				</div>
			</div>
		</a>
	</section>

	<a sveltekit:prefetch href="/">
		<section class="toast ">
			<div class="projekt">
				<h4>Winter 2021</h4>
				<h2>TOAST no.9</h2>
				<p>
					Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint minus saepe qui ex facilis
					ipsa dolorem eum, maiores quas maxime? Adipisci cumque magnam fugit ratione excepturi
					ipsum reiciendis nulla beatae soluta exercitationem praesentium dolorum sapiente ea alias
					perferendis a, nemo quas. Architecto aliquid nobis repellat cum mollitia quidem nostrum
					veritatis!
				</p>
			</div>
			<div>
				<img src="Group 64.svg" alt="Toast logo" />
			</div>
		</section>
	</a>
</section>

<a sveltekit:prefetch href="/">
	<section id="about-me" class="about">
		<div class="projekt">
			<h2>About me</h2>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint minus saepe qui ex facilis
				ipsa dolorem eum, maiores quas maxime? Adipisci cumque magnam fugit ratione excepturi ipsum
				reiciendis nulla beatae soluta exercitationem praesentium dolorum sapiente ea alias
				perferendis a, nemo quas. Architecto aliquid nobis repellat cum mollitia quidem nostrum
				veritatis!
			</p>
		</div>
		<div class="">
			<img src="Mask Group 11.png" alt="Billede af Frederik Milland" />
		</div>
	</section>
</a>

<style>
	.hero {
		padding-top: 3rem;
		width: 100%;
		display: grid;
		place-items: center;
		text-align: center;
		border: solid 2px #42506b;
	}

	.hero img {
		max-width: 110%;
	}

	.hero-text {
		padding-block: 6rem;
		margin-top: -4rem;
	}

	img {
		max-width: 350px;
	}
	.makeimpact {
		padding-block: 2rem;
		width: 100%;
		border-bottom: solid 2px #42506b;
		border-left: solid 2px #42506b;
		border-right: solid 2px #42506b;
		display: grid;
		place-items: center;
	}

	.makeimpact:hover {
		background-color: #e45a5a;
	}
	.makeimpact:hover h2 {
		color: #f6f5f3;
	}
	.makeimpact:hover p {
		color: #f6f5f3;
	}
	.makeimpact:hover h4 {
		color: #f6f5f3;
	}

	.double-section {
		display: grid;
	}

	.projekt {
		margin: 2rem;
	}

	.nb {
		display: grid;
		padding-block: 2rem;
		place-items: center;
		width: 100%;
		border-bottom: solid 2px #42506b;
		border-left: solid 2px #42506b;
		border-right: solid 2px #42506b;
	}

	.vildskud {
		display: grid;
		padding-block: 2rem;
		place-items: center;
		width: 100%;
		border-bottom: solid 2px #42506b;
		border-right: solid 2px #42506b;
		border-left: solid 2px #42506b;
	}

	.double-section img {
		max-width: 350px;
	}

	.nb:hover {
		background-color: #5f739b;
	}
	.nb:hover h2 {
		color: #f6f5f3;
	}
	.nb:hover p {
		color: #f6f5f3;
	}
	.nb:hover h4 {
		color: #f6f5f3;
	}

	.vildskud:hover {
		background-color: #4bbea7;
	}
	.vildskud:hover h2 {
		color: #f6f5f3;
	}
	.vildskud:hover p {
		color: #f6f5f3;
	}
	.vildskud:hover h4 {
		color: #f6f5f3;
	}

	.toast {
		padding-block: 2rem;
		width: 100%;
		border-bottom: solid 2px #42506b;
		border-left: solid 2px #42506b;
		border-right: solid 2px #42506b;
		display: grid;
		place-items: center;
	}

	.toast:hover {
		background-color: #e9ac44;
	}
	.toast:hover h2 {
		color: #f6f5f3;
	}
	.toast:hover p {
		color: #f6f5f3;
	}
	.toast:hover h4 {
		color: #f6f5f3;
	}

	.about {
		padding-block: 2rem;
		width: 100%;
		border-bottom: solid 2px #42506b;
		border-left: solid 2px #42506b;
		border-right: solid 2px #42506b;
		display: grid;
		place-items: center;
	}

	.about:hover {
		background-color: #42506b;
	}
	.about:hover h2 {
		color: #f6f5f3;
	}
	.about:hover p {
		color: #f6f5f3;
	}

	@media (min-width: 600px) {
		.hero {
			padding-top: 0rem;
		}

		.hero-text {
			padding-block: 1.2rem;
			margin-top: -11rem;
			margin-bottom: 1.5rem;
		}

		img {
			max-width: 450px;
		}

		.makeimpact {
			grid-template-columns: 1fr 1fr;
		}

		.double-section {
			grid-template-columns: 1fr 1fr;
		}

		.nb {
			height: 450px;
			grid-template-columns: 1fr 1fr;
		}

		.vildskud {
			height: 450px;
			border-left: none;
			grid-template-columns: 1fr 1fr;
		}

		.toast {
			grid-template-columns: 1fr 1fr;
		}

		.about {
			grid-template-columns: 1fr 1fr;
		}
	}
</style>
