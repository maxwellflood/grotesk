<script>
    export let textLeft
    export let imageLeft
    export let textRight
    export let imageRight
</script>

<section>
    <div class="row flex-align-center">
        <div class="col-hw">
            {#if textLeft}
                <p class="xxl">{textLeft}</p>
            {:else if imageLeft}
                <img src="{imageLeft}" alt="">
            {/if}
        </div>
        <div class="col-hw">
            {#if textRight}
                <p class="xxl">{textRight}</p>
            {:else if imageRight}
                <img src="{imageRight}" alt="">
            {/if}
        </div>
        
    </div>
</section>

<style>

    .col-hw{
        width: 100%;
        padding: 16px;
    }

    .flex-align-center{
        align-items: center;
    }

    p{
        padding: 12.5%;
        max-width: 900px;
        margin: auto;
    }


</style>