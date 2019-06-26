<template>
    <div>
        <heador></heador>
        <h-slider></h-slider>
        <novice></novice>
        <borrow></borrow>
        <money></money>
        <product></product>
        <life></life>
        <Footer></Footer>
        <Navbar></Navbar>
    </div>
</template>

<script>
// 这就算是入口文件 层次分明，比较干净
import Heador from "../public/header.vue"
import HSlider from "./hslider.vue"
import Demo from "./demo.vue"
import Novice from "./novice.vue"
import Borrow from "./borrow.vue"
import Money from "./money.vue"
import Product from "./product.vue"
import Life from "./life.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
export default {
    components: {
        Heador,
        HSlider,
        Demo,
        Novice,
        Borrow,
        Money,
        Product,
        Life,
        Footer,
        Navbar
    }
}
</script>

