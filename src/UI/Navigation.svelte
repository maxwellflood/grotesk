<script>

</script>

<nav class="">
    <div class="nav-logo">
        <img src="../assets/g-logo.svg" alt="">
    </div>
    <div class="nav-menu">
        <div class="nav-button"></div>
    </div>
</nav>

<style>

    nav{
        position: fixed;
        z-index: 1000;
        width: 100%;
        padding: 64px 64px 64px 64px;
        display: flex;
        justify-content: space-between;
    }

    .nav-logo{
        width: 16px;
        height: 24px;
        cursor: pointer;
    }

    .nav-menu{
        height: 24px;
        width: 24px;
        display: flex;
        justify-items: center;
        align-items: center;
        cursor: pointer;
    }

    .nav-menu:hover > .nav-button{
        transform: scale(1.75)
    }

    .nav-button{
        width: 12px;
        height: 12px;
        border-radius: 50%;
        background-color: black;
        transition: transform 0.2s ease; 
    }
    
</style>