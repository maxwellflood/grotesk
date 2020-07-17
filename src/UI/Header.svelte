<script>
    export let pageTitle
    export let pageSubtitle
    export let pageText
</script>

<section>
    <div class="row p-med">
        <div class="col-half">
            <h1 class="p-sm-bottom">{pageTitle}</h1>
            <p>{pageSubtitle}</p>
        </div>
        <div class="col-half">
            <p class="xxl">
                {pageText}
            </p>
        </div>
    </div>
</section>


<style>
    section{
        width: 100%;
        padding: 0 48px;
        background-color: var(--white);
    }

    .row{
        width: 100%;
        /* background-color: antiquewhite; */
        display: flex;
        justify-content: space-between;
    }

    .col-half{
        width: 50%;
        padding-left: 16px;
        padding-right: 16px;
        /* background-color: chocolate; */
    }

    .p-med{
        padding-top: 96px;
        padding-bottom: 96px;
    }

    .p-sm-bottom{
        padding-bottom: 32px;
    }


</style>