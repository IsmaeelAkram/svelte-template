<script>
	let count = 0;
	function increment() {
		count++;
	}
</script>

<main>
	<div class="p-3">
		<h1>Let's count!</h1>
		<p>Current: {count}</p>
		<button class="btn btn-primary" on:click={increment}>Increment</button>
	</div>
</main>
