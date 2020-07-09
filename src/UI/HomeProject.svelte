<script>
    export let image
    export let projectTitle
</script>

<div class="home-project-wrapper">
    <h2>{projectTitle}</h2>
    <div class="project-image-wrapper">
        <img src="{image}" alt="">
    </div>
</div>

<style>
    .home-project-wrapper{
        width: 100vw;
        padding: 64px;
        background-color: var(--white);
    }
</style>