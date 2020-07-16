<script>
    export let splashHeader
    export let splashSubheader
</script>

<section class="splash-wrapper">
    {#if splashHeader && splashSubheader}
        <h1>{splashHeader}</h1>
        <p class="small">{splashSubheader}</p>
    {:else if splashSubheader}
        <p class="small">{splashSubheader}</p>
    {:else if splashHeader}
        <h1>{splashHeader}</h1>
    {:else}
    {/if}
</section>

<style>
    .splash-wrapper{
        position: relative;
        width: 100vw;
        height: 96vh;
        background-color: var(--grey);
        padding: 64px;
        display: flex;
        align-items: center;
    }
</style>