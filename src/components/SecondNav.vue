<script setup>
</script>


<template>

    <div class="container d-flex">
        <a href="#">
            <img class="logo" src="../assets/logo2.png" alt="">
        </a>
        <ul class="left">
            <li><a class="active" href="#">CATALOG</a></li>
            <div class="left-arrow">
                <i class="fa-solid fa-chevron-left"></i>
                <li><a class="inactive underline" href="#">SOLUTIONS</a></li>
                <li><a class="inactive hide-mob" href="#">NEWS</a></li>
                <li><a class="inactive hide-mob" href="#">PROJECTS</a></li>
                <i class="fa-solid fa-chevron-right"></i>
            </div>
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

.fa-chevron-left {
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

.container {
    background-color: #A3846B;
    color: white;
    justify-content: space-between;
    padding: 10px 80px 19px 84px;
}

.left {
    gap: 30px;
    display: flex;
    align-items: center;
}

.left-arrow {
    gap: 30px;
    display: flex;
    align-items: center;
}

.user {
    gap: 10px;
}

.hide-des {
    display: none;
}

@media(max-width: 768px) {
    .hide-des {
        display: flex;
    }

    .hide-mob {
        display: none;
    }

    .container {
        background-color: #A3846B;
        color: white;
        gap: 31px;
        padding: 10px 18px 19px 0px;
    }



    .left {
        flex-direction: column;
        gap: 10px;
    }

    .left-arrow {
        display: flex;
        align-items: center;
        gap: 10px;
    }

    .inactive {
        color: white;
    }

    .underline {
        text-decoration: none;
    }
}
</style>