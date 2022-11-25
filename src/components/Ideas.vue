<script setup>

</script>

<template>
    <div class="container">
        <img class="img" src="../assets/ideas/idea.png" alt="idea">
        <div class="top">
            <h3 class="title">The best ideas for sofas</h3>
            <div class="paras">
                <p class="para">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc vulputate libero et velit
                    interdum, ac aliquet odio mattis. Class aptent taciti sociosqu ad litora torquent per conubia
                    nostra, per inceptos himenaeos. Curabitur tempus urna at.</p>
                <div class="show">
                    <span class="more">Show more</span>
                    <i class=" icon fa-solid fa-chevron-right"></i>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
}

.title {
    font-family: 'Bodoni Moda';
    font-style: normal;
    font-weight: 700;
    font-size: 56px;
    line-height: 120%;
}

.more {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 700;
    font-size: 16px;
}

.show {
    display: flex;
    align-items: center;
    gap: 10px;
    border: 1px solid gray;
    border-radius: 800px;
    padding: 10px 15px;
    width: fit-content;
}

.icon {
    font-size: 10px;
}

.top {
    display: flex;
    flex-direction: column;
    gap: 32px;
    color: white;
    background-color: #1E1E1E;
    padding: 110px 56px 70px 56px;
    border-left: 2px solid white;
}

.paras {
    display: flex;
    flex-direction: column;
    gap: 50px;
}

.para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 150%;
    letter-spacing: 0.03em;
    color: white;
    opacity: 0.9;
}

.img {
    width: 55%;
}

@media(max-width: 768px) {
    .container {
        flex-direction: column-reverse;
    }

    .top {

        padding: 36px 16px;
        border: none;
    }

    .img {
        width: 100%;
        height: 400px;
    }

    .title {
        text-align: center;
    }

    .show {

        padding: 20px 0px;
        justify-content: center;
        width: 100%;
    }
}
</style>