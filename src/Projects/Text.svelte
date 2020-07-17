<script>
    export let text
    export let backgroundColor
    export let backgroundColorTop
    export let backgroundColorBottom
    export let textColor
</script>

<section class="fw" style="background-color: {backgroundColor};">
    <div class="row">
        <div class="col-fw">
            <p class="xxl" style="color: {textColor};">{text}</p>
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
        padding: 30vh 16px;
    }

    p{
        font-size: 64px;
        line-height: 80px;
        max-width: 60%;
        margin: auto;
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