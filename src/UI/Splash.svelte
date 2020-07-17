<script>
    export let splashHeader
    export let splashSubheader
    export let splashImg
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
    <div class="image-wrapper">
        <img class="cover" src="{splashImg}" alt="{splashSubheader}">
    </div>
</section>

<style>
    .splash-wrapper{
        position: relative;
        width: 100%;
        height: 96vh;
        background-color: var(--grey);
        padding: 0;
        display: flex;
        align-items: center;
        overflow: hidden;
    }

    img{
        width: 100%;
        height: 100%;
    }

    .cover{
        object-fit: cover;
    }

    .image-wrapper{
        position: absolute;
        width: 100%;
        height: 100%;
        overflow: hidden;
    }
</style>