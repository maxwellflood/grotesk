<script>
    import Splash from '../UI/Splash.svelte'
    import Header from '../UI/Header.svelte'
    import Image from './Image.svelte'
    import ImageFW from './ImageFW.svelte'
    import ImageText from './ImageText.svelte'
    import Text from './Text.svelte'
</script>


<main>
    <Splash
          splashImg = "../assets/images/aethos/aethos-header.png"
    />
    <Header
        pageTitle = "Relax &amp; unwind"
        pageSubtitle = "Aethos Hotels — Branding"
        pageText = "Project intro text. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent in rutrum ipsum. Integer consectetur metus massa, non mattis urna posuere eu. Nunc laoreet elit maximus, cursus magna a, mollis neque."
    />
    <Image
        image = "../assets/images/aethos/aethos-01.png"
    />
    <ImageText
         textRight = "Project quote or interstitial text goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
         imageLeft = "../assets/images/aethos/aethos-02.png"
    />
    <ImageText
         imageLeft = "../assets/images/aethos/aethos-03.png"
         imageRight = "../assets/images/aethos/aethos-04.png"
    />
    <Image
        image = "../assets/images/aethos/aethos-05.png"
        backgroundColorBottom = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-06.png"
        backgroundColor= #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-07.png"
        backgroundColor= #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-08.png"
        backgroundColor= #6E828B
    />
    <Image
        image = "../assets/images/aethos/aethos-09.png"
        backgroundColorTop = #6E828B
    />
    <Image
        image = "../assets/images/aethos/aethos-10.png"
        backgroundColorBottom = #232D37
    />
    <Text
        text="Project quote or interstitial text goes here. Lorem ipsum dolor sit amet, consectetur adipiscing elit."
        textColor = #FFFFFF
        backgroundColor = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-11.png"
        backgroundColorTop = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-12.png"
    />
    <Image
        image = "../assets/images/aethos/aethos-13.png"
    />
    <Image
        image = "../assets/images/aethos/aethos-14.png"
        backgroundColorBottom = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-15.png"
        backgroundColor = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-16.png"
        backgroundColorTop = #232D37
    />
    <Image
        image = "../assets/images/aethos/aethos-17.png"
    />
</main>


<style>

</style>