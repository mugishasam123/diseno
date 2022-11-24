<script setup>

</script>

<template>

    <div class="container">
        <h3 class="title">Featured products</h3>
        <div class="featured">
            <img class="img" src="../assets/featured/feature1.png" alt="featured">
            <img class="img" src="../assets/featured/feature2.png" alt="featured">
            <img class="img" src="../assets/featured/feature3.png" alt="featured">
            <img class="img" src="../assets/featured/feature4.png" alt="featured">
        </div>
    </div>

</template>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    padding: 64px 100px;
    gap: 41px;
    background-color: #EDEAE6;
}

.title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
}

.featured {
    display: flex;
    gap: 15px;
}

.img {
    width: 25%;
    height: 400px;
}

@media(max-width: 768px) {}
</style>