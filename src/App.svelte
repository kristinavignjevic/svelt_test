<script>
	let num = 0;
</script>

<main>
	<button class="btn"
	on:click={() => {num -= 1}}>-</button>
	<p>{num}</p>
	<button class="btn"
	on:click={() => {num += 1}}>+</button>
</main>

<style>
	main {
		background-color: antiquewhite;
		width: 100%;
		height: 100%;
		display: inline-block;
		display: flex;
		justify-content: center;
		align-items: center;
	}
	button {
		width: 80px;
		height: 40px;
	}
	p {
		margin: 0px 10px;
	}
</style>