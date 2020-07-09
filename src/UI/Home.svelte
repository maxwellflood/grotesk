<script>
    import Splash from './Splash.svelte'
    import HomeProject from './HomeProject.svelte'
</script>


<main>
    <Splash/>
    <section class="home-intro">
        <p>
            We’re Grotesk. Where straightforward meets extraordinary.
            <br/><br/>
            We design exceptional brand experiences with an irreverent twinkle in their eye.
            <br/><br/>
            Let us help you experience the joy in creativity.
        </p>
    </section>
    <section class="home-projects">
        <HomeProject
            projectTitle = {"Hello"}
            
        />
        <HomeProject/>
        <HomeProject/>
        <HomeProject/>
    </section>
</main>


<style>
    .home-intro{
        width: 100vw;
        padding: 64px;
        background-color: var(--white);
        display: flex;
        justify-content: flex-end;
    }

    .home-intro p{
        padding: 160px 0;
        font-size: 1.667vw;
        line-height: 1.5;
        max-width: 50%;
    }
</style>