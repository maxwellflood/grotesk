<script>
    import Splash from './Splash.svelte'
    import Header from './Header.svelte'
    import Image from '../Projects/Image.svelte'
    import ImageFW from '../Projects/ImageFW.svelte'
    import ImageText from '../Projects/ImageText.svelte'
    import Text from '../Projects/Text.svelte'
</script>


<main>
    <Splash
          splashImg = "../assets/images/aethos/aethos-header.png"
    />
    <Header/>
    <Image/>
    <ImageText
         
         imageLeft = "../assets/images/portrait-ph.png"
    />
    <ImageText
         imageLeft = "../assets/images/portrait-ph.png"
         imageRight = "../assets/images/portrait-ph.png"
    />
    <ImageFW/>
    <Text/>
    <Image/>
    <ImageText
         imageLeft = "../assets/images/portrait-ph.png"
         imageRight = "../assets/images/portrait-ph.png"
    />
    <Image/>
    <Image/>
</main>


<style>

</style>