<script>

</script>

<section>
    <div class="row p-med">
        <div class="col-half">
            <div class="type-wrapper">
                <!-- <h2>Client</h2>
                <h1>Airgraft</h1>
                <div class="padding-top">
                    <h2>Services</h2>
                    <p class="large">UX, Digital design, Motion design</p>
                </div> -->
                <slot name="text-left"></slot>
            </div>
        </div>
        <div class="col-half">
            <div class="type-wrapper">
                <!-- <h2>About us</h2>
                <p class="large">
                    Dedicated to creating the future of vaporization, Airgraft are a Montreal based product design studio focussed on creating an unparallelled consumer cannabis experience.
                    <br>
                    <br>
                    We worked in close collaboration with Airgraft’s in-house design and develolment team to bring their digital aesthetic to life online.
                </p> -->
                <slot name="text-right"></slot>
            </div>
        </div>
    </div>
</section>


<style>
    section{
        width: 100%;
        padding: 128px 48px 144px;
        background-color: var(--white);
    }
</style>