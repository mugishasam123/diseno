<script setup>
import CatalogueCard from './CatalogueCard.vue';
</script>



<template>
    <div class="container">
        <h3 class="title">Catalog</h3>
        <div class="catalogs">
            <CatalogueCard title='Tessuti'
                description='Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit interdum, ac aliquet odio mattis.'
                image="catalogue1.png" />
            <div class="d-flex">
                <CatalogueCard title='Category' description='Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                    image='category1.png' />
                <CatalogueCard title='Category' description='Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
                    image='category2.png' />
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    padding-bottom: 64px;
    gap: 20px;
}

.title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 120%;
    color: #000000;
}

.catalogs {
    display: flex;
    flex-direction: column;
    gap: 3px;
}

.d-flex {
    display: flex;
    gap: 3px;
}

@media(max-width: 768px) {
    .d-flex {
        flex-direction: column;
    }
}
</style>