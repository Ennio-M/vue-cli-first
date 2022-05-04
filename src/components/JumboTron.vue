<template>
    <div class="jumbo">
        <HelloWorld/>
    </div>
</template>

<script>
import HelloWorld from './HelloWorld.vue'

export default {
    name: 'JumboTron',
    components: {
        HelloWorld
    }
}
</script>

<style lang="scss" scoped>
    .jumbo{
        width: 100%;
        height: 100vh;
        background-image: url(../assets/imgs/jumbo.png);
        background-repeat: no-repeat;
        background-size: contain;
    }
</style>