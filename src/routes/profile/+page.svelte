<script>
    import {afterNavigate} from "$app/navigation";

    afterNavigate(() => {
        console.log('Profile page');
    })
</script>


<a href="/" data-sveltekit-preload-data="tap">Home</a>
<h1>Profile Page</h1>