<script setup>
import Catalog from './Catalog.vue';
</script>


<template>

    <div class="hero">
        <div class="doublePara">
            <div class="bold hide-mob">
                <p>Creativity, pure Italian style and continuous </p>
                <p>research, in order to infuse jacquard fabrics</p>
                <p>that are rich in tradition with contemporary </p>
                <p class="center">spirit.</p>
            </div>
            <div class="hide-des mobile">
                <p>Creativity, pure Italian style and</p>
                <p> continuous research, in order to</p>
                <p>infuse jacquard fabrics that are rich</p>
                <p>in tradition with contemporary spirit.</p>
            </div>

            <div class="second">
                <p> A family tradition of artisan textile production, dedicated to the creation of high-end
                    yarn-dyed
                    jacquard fabrics, all of which are made in Italy.</p>
                <p>Today, the BRIGNOLI brand is widely recognised for its honed stylistic skill, its creative
                    sophistication and its attention to detail.</p>

                <p> Custom solutions to meet the needs of the constantly-evolving residential and hotel sectors; not
                    only
                    classic weaves,</p>
                <p>but also fabrics for accessories that are rich in details and artisan craftsmanship
                </p>
            </div>
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
    padding-left: 43%;
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
    font-size: 54px;
}

.bold {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
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

.hide-des {
    display: none;
}

@media(max-width: 768px) {
    .doublePara {
        font-size: 24px;
    }

    .hide-mob {
        display: none;
    }

    .hero {
        padding: 0px 18px;

    }

    .mobile {
        display: inline;
        font-family: 'Bodoni Moda';
        font-style: normal;
        font-weight: 700;
        font-size: 18px;
        line-height: 27px;
        text-align: center;
    }
}
</style>