<script>
    export let image
    export let backgroundColor
    export let backgroundColorTop
    export let backgroundColorBottom
</script>

<section style="background-color: {backgroundColor};">
    <div class="row">
        <div class="col-fw">
            <img src="{image}" alt="">
        </div>
    </div>
    <div class="background-color-split-wrapper">
        <div class="background-color-top" style="background-color: {backgroundColorTop};"></div>
        <div class="background-color-bottom" style="background-color: {backgroundColorBottom};"></div>
    </div>
</section>

<style>

    section{
        position: relative;
        display: block;
        overflow: hidden;
    }

    .col-fw{
        width: 100%;
        padding: 16px;
    }

    .row{
        position: relative;
        z-index: 10;
    }

    .background-color-split-wrapper{
        position: absolute;
        z-index: 1;
        width: 100vw;
        height: 100%;
        /* background-color: brown; */
        bottom: 0;
        margin-left: -48px;
    }

    .background-color-top, .background-color-bottom{
        position: absolute;
        width: 100%;
        height: 30%;
        /* background-color: blue; */
    }

    .background-color-bottom{
        bottom: 0;
    }


</style>