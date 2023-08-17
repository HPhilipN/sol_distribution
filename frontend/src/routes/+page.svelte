<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p> GUH </p>

<script>
    let count = 0
    function increment(){
        count += 1
    }
</script>

<p>Clicked {count} {count === 1 ? 'time' : 'times'}</p>
<button on:click={increment}>Click</button>