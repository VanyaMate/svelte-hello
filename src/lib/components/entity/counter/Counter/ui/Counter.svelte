<style>
    .title {
        color: red;
    }

    .button {
        padding: 10px;
    }
</style>

<script lang="ts">
    let counter = 0;

    const increment = function () {
        counter += 1;
    };

    const decrement = function () {
        counter -= 1;
    };
</script>

<h1 class="title">{counter}</h1>
<button on:click={increment} class="button">Increment</button>
<button on:click={decrement} class="button">Decrement</button>