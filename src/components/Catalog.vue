<template>
    <div class="container">
        <h3 class="title">Catalog</h3>
        <div class="catalogs">
            <div class="cata">
                <img class="cata-Img" src="../assets/catalogue/catalogue1.png" alt="catalogue">
                <div class="uptext">
                    <div class="cata-text">
                        <h3 class="cat-title">Tessuti</h3>
                        <div class="line"></div>
                        <p class="cat-para">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate
                            libero et velit interdum, ac aliquet odio mattis.</p>
                    </div>
                </div>
            </div>
            <div class="d-flex">
                <div class="cata">
                    <img class="cata-Img" src="../assets/catalogue/category1.png" alt="catalogue">
                    <div class="uptext">
                        <div class="cata-text">
                            <h3 class="cat-title">Category</h3>
                            <div class="line"></div>
                            <p class="cat-para">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        </div>
                    </div>
                </div>

                <div class="cata">
                    <img class="cata-Img" src="../assets/catalogue/category2.png" alt="catalogue">
                    <div class="uptext">
                        <div class="cata-text">
                            <h3 class="cat-title">Category</h3>
                            <div class="line"></div>
                            <p class="cat-para">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
                        </div>
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

.cata {
    position: relative;
    color: white;
    height: 450px;
}

.cat-title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 120%;
    text-align: center;
}

.cat-para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 150%;
    letter-spacing: 0.03em;
    padding-left: 40px;
    color: white;
    opacity: 0.8;
}

.uptext {
    position: absolute;
    z-index: 100;
    left: 25%;
    right: 25%;
    top: 40%;
    bottom: 55%;
}

.cata-Img {
    width: 100%;
    height: 100%;
}

.cata-text {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
}

.line {
    background-color: grey;
    width: 25px;
    height: 1px;
}

@media(max-width: 768px) {
    .cata {
        height: 400px;
    }

    .d-flex {
        flex-direction: column;
    }

    .cat-title {
        font-family: 'Bodoni Moda';
        font-style: normal;
        font-weight: 700;
        font-size: 40px;
        line-height: 50px;
    }

    .cat-para {
        padding: 0px;
    }

    .uptext {
        position: absolute;
        z-index: 100;
        left: 25%;
        right: 25%;
        top: 25%;
        bottom: 55%;
    }
}
</style>