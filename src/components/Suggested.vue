<script setup>

</script>



<template>

    <div class="container">
        <div class="heading">
            <h3 class="title">Products you might like</h3>
            <i class="fa-solid fa-arrow-right-long"></i>
        </div>

        <div class="featured">
            <img class="img" src="../assets/featured/feature1.png" alt="featured">
            <img class="img" src="../assets/featured/feature2.png" alt="featured">
            <img class="img" src="../assets/featured/feature3.png" alt="featured">
            <img class="img" src="../assets/featured/feature4.png" alt="featured">
            <img class="img" src="../assets/featured/half.png" alt="featured">
        </div>
    </div>

</template>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    padding: 64px 0px 64px 100px;
    gap: 41px;
    background-color: #EDEAE6;
    overflow: hidden;
}

.title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
}

.img {
    width: 22%;
    height: 400px;
}

.heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-right: 110px;
}

.featured {
    display: flex;
    gap: 15px;
}



@media(max-width: 768px) {}
</style>