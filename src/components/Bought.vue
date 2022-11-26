<template>
    <div class="container">
        <div class="top">
            <h3 class="title">Top bought product</h3>
            <div class="paras">
                <p class="para">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit
                    interdum, ac
                    aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per
                    inceptos
                    himenaeos. Curabitur tempus urna at turpis condimentum lobortis. Ut commodo efficitur neque. Ut diam
                    quam, semper iaculis condimentum ac, vestibulum eu nisl.</p>

                <p class="para">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit
                    interdum, ac
                    aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per
                    inceptos
                    himenaeos. Curabitur tempus urna at turpis</p>

                <p class="para hide-mob"> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero
                    et velit
                    interdum, ac
                    aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia nostr</p>
            </div>
        </div>
        <img class="img" src="../assets/bought/bought1.png" alt="top">
    </div>
</template>

<style scoped>
.container {
    display: flex;
    padding: 64px 100px;
    gap: 59px;
    background-color: #F5F5F4;
}

.title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 40px;
    line-height: 50px;
}

.top {
    display: flex;
    flex-direction: column;
    gap: 32px;
    width: 496px;
}

.paras {
    display: flex;
    flex-direction: column;
    gap: 20px;

}

.para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 150%;
    letter-spacing: 0.03em;
    color: #2b2b2b;
}

.img {
    width: 50%;
    height: 484px;
}

@media(max-width: 768px) {
    .container {
        flex-direction: column;
        padding: 36px 16px;

    }

    .hide-mob {
        display: none;
    }

    .img {
        width: 100%;
        height: 330px;
    }

    .top {
        width: 100%;
    }
}
</style>