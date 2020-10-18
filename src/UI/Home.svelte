<script>
    import Splash from './Splash.svelte'
    import Header from './Header.svelte'


    let projects = [
        {
            image : '../assets/images/projects/ae.jpg',
            client: 'Aethos'
        },
        {
            image : '../assets/images/projects/ag.jpg',
            client: 'Airgraft'
        },
        {   
            image : '../assets/images/projects/cat.jpg',
            client: 'CAT'
        },
    ]   

</script>


<main>
    <Splash splashSubheader="Project" splashHeader="Airgraft"/>

    <Header>
        <div slot="text-right">
            <h2>Creating brands with character</h2>
            <p class="xxl">
                We’re Grotesk, a creative studio that exists to create compelling and engaging brand experiences through research, strategy and design.
            </p>
        </div>
    </Header>

    <section class="projects">
        {#each projects as project}
            <div class="row padding-bottom">
                <div class="project">
                    <img src="{project.image}" alt="">
                </div>
            </div>
        {/each}
    </section>
    
    <section class="all-projects">
        <div class="row">
            <div class="col-fw">
                 <div class="type-wrapper">
                    <h2>Projects</h2>
                    <p class="xxl">See all projects</p>
                </div>
            </div>
        </div>
    </section>

</main>




<style>
     /* main{
          transform: translateY(120px);
     } */
     .project{
         width: 100%;
     }
     .all-projects{
         padding-top: 128px;
         padding-bottom: 144px;
     }
</style>