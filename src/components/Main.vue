<script>
import Title from './Title.vue';
import Hero from './Hero.vue';
export default {
    data() {
        return {
        }
    },
    components: {
        Title,
        Hero
    }
}
</script>

<template>
    <Title class="colore" />
    <div class="centro">
        <Hero class="immagine" />
        <p>test</p>
    </div>
</template>

<style scoped>
.colore {
    color: red;
    font-size: 2em;
    text-align: center;
}

.immagine {
    width: 30%;
    height: 30%;
}

.centro {
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
