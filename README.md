# Svelte switch

A simple switch component for sveltev3. Example can be found [here](https://svelte.dev/repl/35d77f2ab11e4197a19ffd8e7c4ac74e?version=3.9.1).

### Installing

`npm i -D svelte-switch`

### Usage

```
<script>
	import Switch from './Switch.svelte';

	let yes = false;
</script>

<Switch bind:checked={yes}></Switch>
```

## License

This project is licensed under the MIT License.
