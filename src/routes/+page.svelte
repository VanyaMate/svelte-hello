<script>
    import Counter from '@entity/counter/Counter/ui/Counter.svelte';
</script>

<nav>
    <ul>
        <li>
            <a href="/" data-sveltekit-preload-data="tap">Home</a>
            <a href="/profile" data-sveltekit-preload-data="tap">Profile</a>
        </li>
    </ul>
</nav>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<Counter/>
