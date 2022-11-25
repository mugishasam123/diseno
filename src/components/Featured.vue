<script setup>

</script>

<template>

    <div class="container">
        <h3 class="title">Featured products</h3>
        <div class="featured">

            <div class="card">
                <img class="img" src="../assets/featured/feature1.png" alt="featured">
                <div class=" arrows ">
                    <div class="hide-des between">
                        <img class="icon" src="../assets/left.png" alt="left-arrow">
                        <img class="icon" src="../assets/right.png" alt="right-arrow">
                    </div>
                </div>
                <div class="description hide-des">
                    <p class="paragraph">Lorem ipsum dolor sit amet</p>
                    <div class="circles">
                        <div class="circle red"></div>
                        <div class="circle gray"></div>
                        <div class="circle green"></div>
                        <div class="circle black"></div>
                        <span class="number">+20</span>
                    </div>
                </div>
            </div>

            <div class="card">
                <img class="img" src="../assets/featured/feature2.png" alt="featured">
                <div class=" arrows ">
                    <div class="hide-des between">
                        <img class="icon" src="../assets/left.png" alt="left-arrow">
                        <img class="icon" src="../assets/right.png" alt="right-arrow">
                    </div>
                </div>
                <div class="description hide-des">
                    <p class="paragraph">Lorem ipsum dolor sit amet</p>
                    <div class="circles">
                        <div class="circle red"></div>
                        <div class="circle gray"></div>
                        <div class="circle green"></div>
                        <div class="circle black"></div>
                        <span class="number">+20</span>
                    </div>
                </div>
            </div>

            <div class="card">
                <img class="img" src="../assets/featured/feature3.png" alt="featured">
                <div class=" arrows ">
                    <div class="hide-des between">
                        <img class="icon" src="../assets/left.png" alt="left-arrow">
                        <img class="icon" src="../assets/right.png" alt="right-arrow">
                    </div>
                </div>
                <div class="description hide-des">
                    <p class="paragraph">Lorem ipsum dolor sit amet</p>
                    <div class="circles">
                        <div class="circle red"></div>
                        <div class="circle gray"></div>
                        <div class="circle green"></div>
                        <div class="circle black"></div>
                        <span class="number">+20</span>
                    </div>
                </div>
            </div>

            <div class="card">
                <img class="img" src="../assets/featured/feature4.png" alt="featured">
                <div class=" arrows ">
                    <div class="hide-des between">
                        <img class="icon" src="../assets/left.png" alt="left-arrow">
                        <img class="icon" src="../assets/right.png" alt="right-arrow">
                    </div>
                </div>
                <div class="description hide-des">
                    <p class="paragraph">Lorem ipsum dolor sit amet</p>
                    <div class="circles">
                        <div class="circle red"></div>
                        <div class="circle gray"></div>
                        <div class="circle green"></div>
                        <div class="circle black"></div>
                        <span class="number">+20</span>
                    </div>
                </div>
            </div>


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
    width: 100%;
    height: 400px;
}

.card {
    width: 25%;
}

.hide-des {
    display: none;
}

@media(max-width: 768px) {
    .arrows {
        position: absolute;
        z-index: 100;
        left: 0%;
        right: 0%;
        top: 30%;
        bottom: 50%;
        height: fit-content;
    }

    .between {
        display: flex;
        padding: 0px 9px;
        justify-content: space-between;
        align-items: center;
    }

    .icon {
        width: 35px;
        height: 35px;
    }

    .container {
        padding: 44px 16px 64px 16px;
    }

    .featured {
        flex-direction: column;
        gap: 50px;
    }

    .paragraph {
        font-family: 'Raleway';
        font-style: normal;
        font-weight: 700;
        font-size: 18px;
        line-height: 28px;
        text-align: center;
        letter-spacing: 0.02em;
    }

    .number {
        font-family: 'Raleway';
        font-style: normal;
        font-weight: 500;
        font-size: 14px;
        line-height: 20px;
        letter-spacing: 0.03em;
    }

    .img {
        width: 100%;
        height: 328px;
    }

    .circle {
        height: 20px;
        width: 20px;
        border-radius: 100%;
    }

    .circles {
        display: flex;
        gap: 12px;
    }

    .description {
        display: flex;
        flex-direction: column;
        gap: 35px;
        align-items: center;
    }

    .red {
        background-color: #973528;
    }

    .gray {
        background-color: #9A9EA3;
    }

    .green {
        background-color: #00513C;
    }

    .black {
        background-color: #1E1E1E;
    }

    .card {
        width: 100%;
        display: flex;
        flex-direction: column;
        gap: 20px;
        position: relative;
    }
}
</style>