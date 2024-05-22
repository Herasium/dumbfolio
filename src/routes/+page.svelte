<script>
	import bg from '$lib/img/bg.png';
	import Icon from '@iconify/svelte';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<img src={bg} id="bg" />

<div id="container">
	<div class="big">👋 Hello, I'm <strong>Hera</strong></div>
	<div>I design and code dumb projects like this website</div>
	<br />
	<div class="row-container">
		<ul>
			<div>I know</div>
			<br />
			<li>Python (75%)</li>
			<li>Js (70%)</li>
			<li>Lua (90%)</li>
			<li>Html (85%)</li>
			<li>Css (75%)</li>
			<li>Svelte (65%)</li>
		</ul>
		<ul>
			<div>I Did</div>
			<br />
			<li><a href="https://blockcoin.social">Blockcoin</a></li>
			<li><a href="https://herasium.dev">This Website</a></li>
			<li><a href="https://tatom.herasium.dev">Tatom</a></li>
			<li><a href="https://www.roblox.com/users/2698968750/profile">Roblox Games</a></li>
			<li><a href="https://scratch.mit.edu/users/Herasium/">Tons of scratching</a></li>
			<li>Many other things</li>
		</ul>
	</div>
	<br />
	<div class="row-container">
		<a href="https://discordapp.com/users/732949533662642316"
			><Icon icon="ic:baseline-discord" style="font-size: 2vw;" /></a
		>
		<a href="https://github.com/Herasium"><Icon icon="mdi:github" style="font-size: 2vw;" /></a>
	</div>
</div>

<style>
	* {
		color: white;
		font-family: 'Montserrat', sans-serif;
	}
	#bg {
		z-index: -1;
		width: 100%;
		height: 100%;
		position: fixed;
		top: 0;
		left: 0;
	}
	#container {
		width: 100%;
		height: 100%;
		position: fixed;
		top: 0;
		left: 0;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
	}
	.big {
		font-size: 3vw;
		font-weight: 500;
	}
	.row-container {
		width: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: row;
	}
	ul {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
	}
</style>
