<script>
    let counter = 0;
</script>

<svelte:head>
    <title>Home</title>
    <meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
    <h1>Welcome!</h1>
    <button
        on:click={() => {
            counter += 1;
        }}>+</button
    >
    <span>{counter}</span>
    <button
        on:click={() => {
            counter -= 1;
        }}>-</button
    >
</section>

<style>
</style>
