<script>
	import Button from '@smui/button';
	export let name;
</script>

<svelte:head>
	<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,600,700">
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto+Mono">
</svelte:head>

<h1 class="mdc-typography--headline1">Hello {name}!</h1>
<Button on:click={() => alert('clicked!')}>Just a Button</Button>