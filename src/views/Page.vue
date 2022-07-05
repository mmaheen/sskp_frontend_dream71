<script>
//import { RouterLink, RouterView } from 'vue-router'
import Hello from '@/components/Hello.vue'
import Navbar from '@/components/Navbar.vue'
import Slider from '@/components/Slider.vue'
import Body from '@/components/Body.vue'
import Footer from '@/components/Footer.vue'
import News from '@/components/News.vue'

export default {
    components: {
        Hello, Navbar, Slider, Body, Footer, News
    }
}

</script>



<template>
    <div>
        <Navbar></Navbar>
        <Slider></Slider>
        <News></News>

        <Body></Body>
        <Footer></Footer>
    </div>
</template>
