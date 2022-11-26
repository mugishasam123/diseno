<script setup>

</script>


<template>

    <nav class="container  d-flex">
        <a href="">
            <img class="logo hide-mob" src="../assets/deslogo.png" alt="">
            <img class="logo hide-des" src="../assets/deslogo1.png" alt="">
        </a>
        <div class="left d-flex">
            <div class="user d-flex">
                <img class="vector" src="../assets/Vector.png" alt="menu">
                <span class="log hide-mob">LOG IN</span>
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
    font-size: 16px;
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

.container {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
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

.hide-des {
    display: none;
}

@media(max-width: 768px) {
    .container {
        position: inherit;
        background-color: #000000;
        color: white;
        justify-content: space-between;
        padding: 16px 20px 19px 16px;

    }

    .hide-des {
        display: flex;
    }

    .hide-mob {
        display: none;
    }

    .menu {
        width: 36px;
        height: 36px;
    }

    .vector {
        width: 24px;
        height: 24px;
    }

    .logo {
        width: 50px;
        height: 56px;
    }

}
</style>