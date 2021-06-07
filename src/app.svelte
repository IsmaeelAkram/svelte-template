<script>
	let count = 0;
	function increment() {
		count++;
	}
	function decrement() {
		count--;
	}
</script>

<main class="p-3">
	<h1>Let's count!</h1>
	<p>Current: <strong>{count}</strong></p>
	<button class="btn btn-primary" on:click={increment}>Increment</button>
	<button class="btn btn-danger" on:click={decrement}>Decrement</button>
</main>
