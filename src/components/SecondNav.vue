<script>

export default {

    methods: {
        scrollRight() {
            const navMenu = document.querySelector('.nav-links')
            const prevTrans = new WebKitCSSMatrix(window.getComputedStyle(navMenu).transform)
            if (prevTrans.m41 < 0) {
                navMenu.style.transform = `translateX(${(prevTrans.m41 + 100)}px)`
            }

            const NextTrans = new WebKitCSSMatrix(window.getComputedStyle(navMenu).transform)
        },
        scrollLeft() {
            const navMenu = document.querySelector('.nav-links')
            const prevTrans = new WebKitCSSMatrix(window.getComputedStyle(navMenu).transform)
            if (-prevTrans.m41 < 660) {
                navMenu.style.transform = `translateX(${(prevTrans.m41 - 110)}px)`
            }
            const NextTrans = new WebKitCSSMatrix(window.getComputedStyle(navMenu).transform)
        }
    }
}
</script>


<template>

    <div class="container d-flex">
        <a href="#">
            <img class="logo" src="../assets/logo2.png" alt="">
        </a>
        <div class="left">
            <a class="active" href="#">CATALOG</a>
            <div class="left-arrow">
                <i @click="scrollRight" class="fa-solid fa-chevron-left"></i>
                <div class="des-menu">
                    <ul class="nav-links">
                        <li><a class="inactive underline" href="#">SOLUTIONS</a></li>
                        <li><a class="inactive hide-mob" href="#">NEWS</a></li>
                        <li><a class="inactive hide-mob" href="#">PROJECTS</a></li>
                        <li><a class="inactive hide-mob" href="#">ABOUT</a></li>
                        <li><a class="inactive hide-mob" href="#">PRESS</a></li>
                        <li><a class="inactive hide-mob" href="#">CONTACT</a></li>
                        <li><a class="inactive hide-mob" href="#">TEXTURES</a></li>
                        <li><a class="inactive hide-mob" href="#">INSPIRATION</a></li>
                    </ul>
                </div>
                <i @click="scrollLeft" class="fa-solid fa-chevron-right"></i>
            </div>
        </div>
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

.nav-links {
    display: flex;
    align-items: center;
    gap: 30px;
    transition: transform 0.8s ease-out;
    transform: translateX(0px);
}

.des-menu {
    width: 348.9px;
    overflow: hidden;
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
    position: fixed;
    top: 92px;
    left: 0;
    right: 0;
    z-index: 1000;
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
    gap: 20px;
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
    .container {
        position: inherit;
    }

    .hide-des {
        display: flex;
    }

    .nav-links {
        gap: 0px;
        width: fit-content;
    }

    .des-menu {
        gap: 0px;
        width: fit-content;
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