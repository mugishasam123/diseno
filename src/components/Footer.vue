<script setup>

</script>

<template>
    <div class="container">
        <div class="part-one">
            <img src="../assets/logos/footerLogo.png" alt="logo">
            <ul class="contact">
                <li><a class="same underline" href="#"> Contatti</a></li>
                <li><i class="social fa-brands fa-instagram"></i></li>
                <li><i class="social fa-brands fa-facebook"></i></li>
            </ul>
        </div>
        <div class="second-part">
            <p class="log-para color">Dal 1947 lo spirito imprenditoriale <br> <span class="white">MARTINELLIGINETTO
                </span> si fonda sulle competenze tecniche, l’utilizzo
                delle tecnologie tessili più avanzate e sulla capacità di mobilitare energie professionali e creative in
                grado di innovare il prodotto a tutti i livelli.</p>
            <div class="link-div">
                <h3 class="headers">Settori</h3>
                <ul class="links">
                    <li><a href="#">Filati</a></li>
                    <li><a href="#">Filati</a></li>
                    <li><a href="#">Filati</a></li>
                    <li><a href="#">Filati</a></li>
                </ul>
            </div>
            <div class="link-div">
                <h3 class="headers">INNOVAZIONE</h3>
                <ul class="links">
                    <li><a href="#">Creatività e Design</a></li>
                    <li><a href="#">Realtà produttiva</a></li>
                    <li><a href="#">Vision Digitale</a></li>
                </ul>
            </div>
            <div class="link-div">
                <h3 class="headers">Responsabilità</h3>
                <ul class="links">
                    <li><a href="#">Economica</a></li>
                    <li><a href="#">Ambientale</a></li>
                    <li><a href="#">Sociale</a></li>
                </ul>
            </div>
            <div class="link-div">
                <h3 class="headers">CARRIERA</h3>
                <ul class="links">
                    <li><a href="#">Giovani</a></li>
                    <li><a href="#">Scuola lavoro</a></li>
                    <li><a href="#">Lavora con noi</a></li>
                </ul>
            </div>
        </div>


        <div class="line"></div>
        <ul class="logos">
            <li class="gray"><a href="#"><img class="gray" src="../assets/logos/logo1.png" alt="footer-logo"></a></li>
            <li class="gray"><a href="#"><img src="../assets/logos/logo2.png" alt="footer-logo"></a></li>
            <li><a href="#"><img src="../assets/logos/logo3.png" alt="footer-logo"></a></li>
            <li><a href="#"><img src="../assets/logos/logo4.png" alt="footer-logo"></a></li>
            <li><a href="#"><img src="../assets/logos/logo5.png" alt="footer-logo"></a></li>
        </ul>
        <div class="line"></div>
        <div class="third-part">
            <ul class="privacy">
                <li><a class="same underline" href="#">Privacy</a></li>
                <li><a class="same underline" href="#">Cookie policy</a></li>
            </ul>
            <p class="down-para same">Martinelli Ginetto S.p.A - C.F. e Partita Iva 03403660164 Cap.Sociale 10.000.000
                I.v.
                REA: BG – 375519
            </p>
        </div>
    </div>
</template>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    gap: 32px;
    border-top: 2px solid white;
    padding: 60px 110px 10px 108px;
    background-color: #1E1E1E;

}

.contact {
    display: flex;
    gap: 32px;
    align-items: center;
}

.gray {
    color: gray;
}

.down-para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 11px;
    line-height: 28px;
    letter-spacing: 2px;
    color: gray;
}

.social {
    color: white;
}

.headers {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 700;
    font-size: 12px;
    line-height: 28px;
    color: white;
}

.link-div {
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.second-part {
    display: flex;
    justify-content: space-between;
    padding-right: 120px
}

.logos {
    display: flex;
    justify-content: space-between;
}

.links {
    display: flex;
    flex-direction: column;
    gap: 16px;
}

.same {

    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 11px;
    line-height: 28px;
    letter-spacing: 2px;
}

.underline {
    text-decoration: underline;
}

.links>li>a {

    font-family: 'Raleway';
    font-style: normal;
    font-weight: 400;
    font-size: 12px;
    line-height: 28px;
    letter-spacing: 2px;
}

.white {
    color: white;
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 700;
    font-size: 12px;
    line-height: 28px;
}

.part-one {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.third-part {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.privacy {
    display: flex;
    gap: 10px;
    align-items: center;
}

.line {
    width: 100%;
    height: 1px;
    background-color: gray;
}

.log-para {
    font-family: 'Raleway';
    font-style: normal;
    font-weight: 300;
    font-size: 12px;
    line-height: 20px;
    letter-spacing: 2px;
    width: 400px;
}

a {
    color: white;
    opacity: 0.6;
}

.color {
    color: gray;
}


@media(max-width: 768px) {}
</style>