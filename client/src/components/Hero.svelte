<script>
	import Profile from '../components/Profile.svelte';
</script>

<div class="hero flex justify-center items-center relative">
	<div class="wrapper relative z-10">
		<Profile />
	</div>
</div>

<style>
	.hero {
		position: relative;
		height: 30vh;
		background: url(https://opgg-static.akamaized.net/meta/images/lol/champion/centered/Aphelios_18.jpg?image=c_crop,w_1280,y_-120,x_0)
			no-repeat center center;
		background-size: cover;
	}
	.hero::before {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		background: rgba(0, 0, 0, 0.4); /* Semi-transparent overlay */
		z-index: 1;
	}
	.hero::after {
		content: '';
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		background: url(https://s-lol-web.op.gg/static/images/site/summoner/mask_dark.svg) no-repeat
			center center;
		background-size: cover;
		z-index: 2;
	}
	.wrapper {
		position: relative;
		z-index: 3; /* Ensure the content is above the pseudo-elements */
	}
</style>
