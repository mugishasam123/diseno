<script setup>
import Catalog from './Catalog.vue';
</script>


<template>

    <div class="hero">
        <div class="doublePara">
            <div class="bold">
                <p>Creativity, pure Italian style and continuous research, in order to infuse jacquard fabrics that are
                    rich
                    in tradition with contemporary </p>
                <span class="center">spirit.</span>
            </div>

            <p class="second">A family tradition of artisan textile production, dedicated to the creation of high-end
                yarn-dyed
                jacquard fabrics, all of which are made in Italy.

                Today, the BRIGNOLI brand is widely recognised for its honed stylistic skill, its creative
                sophistication and its attention to detail.

                Custom solutions to meet the needs of the constantly-evolving residential and hotel sectors; not only
                classic weaves,

                but also fabrics for accessories that are rich in details and artisan craftsmanship</p>
        </div>
        <Catalog />
    </div>

</template>

<style scoped>
.hero {
    padding: 0px 100px;
    display: flex;
    flex-direction: column;
    gap: 60px;
    background-color: #F5F5F4;
}

.center {
    text-align: center;
}

.d-flex {
    display: flex;
    align-items: center;
}

.doublePara {
    padding-top: 64px;
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.bold {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    color: #000000;
    line-height: 120%;
}

.second {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 150%;

    text-align: center;
    letter-spacing: 0.03em;

    color: #000000;
}


@media(max-width: 768px) {}
</style>