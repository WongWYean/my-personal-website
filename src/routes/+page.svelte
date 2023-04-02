<script lang="ts">
	import { onMount } from 'svelte';

	let color: string = '#000000';

	function handleColorChange(event: Event) {
		color = (event.target as HTMLInputElement).value;
	}

	onMount(() => {
		console.log(`Initial color: ${color}`);
	});
</script>

<label for="color-picker">Select a color:</label>
<input type="color" id="color-picker" bind:value={color} on:change={handleColorChange} />

<p>You chose: {color}</p>

<!-- Color Picker together with conversion -->
<!-- Color Picker with Name -->
<!-- Add variations -->
<!-- Add color harmonies -->
<!-- Add color blindness -->
<!-- Add contrast checker -->
