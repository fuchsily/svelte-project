<script lang="ts">
	import TaskForm from "./components/task-form.svelte";
	let name = "Task App";
</script>

<main>
	<h1>{name}!</h1>
	<TaskForm/>
</main>

<style>
	main {
		text-align: center;
		margin: 1em auto;
		max-width: 800px;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
</style>