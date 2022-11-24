<script setup>
</script>


<template>

    <div class="container navbar d-flex">
        <a href="#">
            <img class="logo" src="../assets/logo2.png" alt="">
        </a>
        <ul class="left d-flex">
            <li><a class="active" href="#">CATALOG</a></li>
            <i class="fa-solid fa-chevron-left"></i>
            <li><a class="inactive underline" href="#">SOLUTIONS</a></li>
            <li><a class="inactive" href="#">NEWS</a></li>
            <li><a class="inactive" href="#">PROJECTS</a></li>
            <i class="fa-solid fa-chevron-right"></i>
        </ul>
    </div>

</template>

<style scoped>
.d-flex {
    display: flex;
    align-items: center;
}

.active {
    color: white;
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 700;
    font-size: 20px;
    line-height: 29px;
}
.fa-chevron-left{
    opacity: 0.4;
}

.underline {
    text-decoration-line: underline;
}

.inactive {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
    line-height: 29px;

    color: rgba(255, 255, 255, 0.713);
}

.logo {
    width: 150px;
    height: 50px;
}

.navbar {
    background-color: #A3846B;
    color: white;
    justify-content: space-between;
    padding: 10px 80px 19px 84px;
}

.left {
    gap: 30px;
}

.user {
    gap: 10px;
}

@media(max-width: 768px) {}
</style>