<script>
	import Card from "./components/Card.svelte";
</script>

<style>
	.circle-top {
		position: fixed;
		right: 52%;
		bottom: 35%;
	}
	.circle-bottom {
		position: fixed;
		top: 50%;
		left: 48%;
	}
</style>

<main>
	<div class="circle-top"><img src="./assets/bg-pattern-top.svg" alt="" /></div>
	<div class="circle-bottom">
		<img src="./assets/bg-pattern-bottom.svg" alt="" />
	</div>

	<Card />
</main>
