<script>
    import Link from "./Link.svelte";
    import Button from './Button.svelte';

    let buttons = ['Contact Us', "About Us", "Services"];
</script>


<style>
    .border-right{
        height: 10px;
        width: 2px;
        background-color: aqua;
        display: inline-block;
        margin-right: 0.5rem;
        transform: skew(-5deg);
    }
</style>

<nav>
    {#each buttons as buttonText, i}
        {#if i < buttons.length-1}
            <Link href="/testing">{buttonText}</Link>
            <div class="border-right"></div>
            {:else}
            <Link >{buttonText}</Link>
        {/if}
    {/each}
</nav>