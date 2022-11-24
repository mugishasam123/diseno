<script setup>

</script>


<template>

    <nav class="container navbar d-flex">
        <a href="">
            <img class="logo" src="../assets/deslogo.png" alt="">
        </a>
        <div class="left d-flex">
            <div class="user d-flex">
                <img class="vector" src="../assets/Vector.png" alt="menu">
                <span class="log">LOG IN</span>
            </div>
            <img class="menu" src="../assets/Menu.png" alt="menu">
        </div>
    </nav>

</template>

<style scoped>
.d-flex {
    display: flex;
    align-items: center;
}

.log {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 24px;
}

.vector {
    width: 15px;
    height: 15px;
}

.menu {
    width: 30px;
    height: 30px;
}

.logo {
    width: 200px;
    height: 50px;
}

.navbar {
    background-color: #000000;
    color: white;
    justify-content: space-between;
    padding: 19px 80px 19px 84px;
}

.left {
    gap: 30px;
    color: white;
}

.user {
    gap: 10px;
}

@media(max-width: 768px) {}
</style>