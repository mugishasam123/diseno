<script setup>
import { defineComponent } from 'vue'
import { computed } from 'vue'


defineProps({
    title: String,
    description: String,
    image: String,
})

defineComponent({
    computed: {
        imageSrc() {
            return new URL(`./assets/${this.image}`, import.meta.url).href;
        }
    }
}) 
</script>


<template>

    <div class="cata">
        <img class="cata-Img" src="../assets/catalogue/catalogue1.png" alt="catalogue">
        <div class="uptext">
            <div class="cata-text">
                <h3 class="cat-title">{{ title }}</h3>
                <div class="line"></div>
                <p class="cat-para">{{ description }}</p>
            </div>
        </div>

    </div>

</template>

<style scoped>
.cata {
    position: relative;
    color: white;
    height: 450px;
}

.cat-title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 120%;
    text-align: center;
}

.cat-para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 150%;
    letter-spacing: 0.03em;
    padding-left: 40px;
    color: white;
    opacity: 0.8;
}

.uptext {
    position: absolute;
    z-index: 100;
    left: 25%;
    right: 25%;
    top: 40%;
    bottom: 55%;
}

.cata-Img {
    width: 100%;
    height: 100%;
}

.cata-text {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.line {
    background-color: grey;
    width: 25px;
    height: 1px;
}

@media(max-width: 768px) {
    .cat-title {
        font-family: 'Bodoni Moda';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 50px;
    }

    .cat-para {
        padding: 0px;
    }

    .uptext {
        position: absolute;
        z-index: 100;
        left: 25%;
        right: 25%;
        top: 25%;
        bottom: 55%;
    }
}
</style>