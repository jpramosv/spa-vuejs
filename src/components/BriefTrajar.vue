<template>
    <section class="brief">
        <div class="brief-container">
            <h1> Depoimentos</h1>
            <img src="@/assets/will.png" alt="will">
            <div class="seta">
                <p>“Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por intermédio de meu pai, que já
                    tem
                    uma história de décadas com o querido Renee.</p>
            </div>

            <h3>William H. M. Garey</h3>
            <h4>Advogado | Nelson Garey Advogados Associados</h4>
        </div>
        <div class="brief-container">
            <h1> Depoimentos</h1>
            <img src="@/assets/josi.png" alt="will">
            <div class="seta">
                <p>“Há mais de 10 anos sou cliente da Renee Trajar. A qualidade, caimento e possibilidade de
                    customização das roupas, aliados ao excelente atendimento e prazo de entrega são fatores decisivos
                    para mim.”</p>
            </div>

            <h3>Josimar Henrique da Silva</h3>
            <h4>Diretor Presidente | Grupo Hebron</h4>

        </div>
        <div class="brief-container">
            <h1> Depoimentos</h1>
            <img src="@/assets/domi.png" alt="will">
            <div class="seta">
                <p>“Tenho a honra de afirmar que enquanto nossas vidas perdurarem o meu conceito é sempre melhor em
                    relação ao Renee Trajar, sua pessoa, ao profissional competente e idôneo, sempre pontual, atencioso
                    e preocupado em atender da melhor maneira os anseios de seus clientes, incluindo este signatário.”
                </p>
            </div>

            <h3>José Mauro Marques</h3>
            <h4>Advogado</h4>

        </div>
        <div class="left" @click="plusDivs(-1)"></div>
        <div class="right" @click="plusDivs(1)"></div>
    </section>
</template>
<script>

export default {
    name: 'BriefTrajar',
    data() {
        return {
            slideIndex: 1,
        }
    },
    methods: {
        plusDivs(n) {
            this.showDivs(this.slideIndex += n)
        },
        showDivs(n) {
            let i;
            let x = document.getElementsByClassName("brief-container");
            if (n > x.length) { this.slideIndex = 1 }
            if (n < 1) { this.slideIndex = x.length }
            for (i = 0; i < x.length; i++) {
                x[i].style.display = "none";
            }
            x[this.slideIndex - 1].style.display = "flex";
        }


    },
    mounted() {
        this.showDivs(this.slideIndex)
    }
}

</script>


<style>
.left {
    cursor: pointer;
    left: calc(10% - 50px);
    transform: rotate(45deg);
}

.right {
    cursor: pointer;
    right: calc(10% - 50px);
    transform: rotate(-135deg);

}

.right,
.left {
    position: absolute;
    top: 50%;
    padding: 15px;
    box-shadow: 2px -2px 0 1px #BE9667 inset;
    border: solid transparent;
    border-width: 0 0 2px 2px;

}

.brief {
    background: #264450;
    position: relative;


}

.brief-container {
    max-width: 764px;
    height: 408px;
    margin: 0 auto;
    flex-direction: column;
    align-items: center;
    align-content: space-between;
    padding: 30px;
    display: none;
    position: relative;
}

.brief-container img {
    width: 121px;
    margin-top: 20px;
    border: 2px solid #BE9667;
    border-radius: 50%;
}

.brief-container p {
    font-family: 'Cormorant';
    font-style: italic;
    font-weight: 300;
    font-size: 1.5em;
    line-height: 31px;
    text-align: center;
    color: #C4C4C4;
}

.brief-container h1 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 300;
    font-size: 3em;
    line-height: 46px;
    height: 46px;
    color: #F2F2F2;

}

.brief-container h3 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 400;
    font-size: 1.4em;
    line-height: 24px;
    text-align: center;
    color: #BE9667;
    margin-top: 20px;
    margin-bottom: -20px;
}

.brief-container h4 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 17px;
    text-align: center;
    color: #949494;
}

@media(max-width:999px) {

    .seta {
        max-width: 500px;
    }

    .left {

        left: 5%;

    }

    .right {
        right: 5%;

    }

    .brief-container h1 {
        font-family: 'Cormorant';
        font-style: normal;
        font-weight: 300;
        font-size: 2.5em;
        line-height: 46px;
        height: 46px;
        color: #F2F2F2;

    }

    .brief-container p {
        font-family: 'Cormorant';
        font-style: italic;
        font-weight: 300;
        font-size: 1.3em;
        line-height: 31px;
        text-align: center;
        color: #C4C4C4;
    }

    .brief-container h3 {
        font-family: 'Cormorant';
        font-style: normal;
        font-weight: 400;
        font-size: 1.3em;
        line-height: 24px;
        text-align: center;
        color: #BE9667;
        margin-top: 20px;
        margin-bottom: -20px;
    }

    .brief-container h4 {
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 0.9em;
        line-height: 17px;
        text-align: center;
        color: #949494;
    }
}

@media(max-width:600px) {
    .brief {
        height: 600px;
        display: flex;
        align-items: center;
    }


    .seta {
        max-width: 300px;

    }

    .left {

        left: 5%;

    }

    .right {
        right: 5%;

    }

    .brief-container h1 {
        font-family: 'Cormorant';
        font-style: normal;
        font-weight: 300;
        font-size: 2.3em;
        line-height: 46px;
        height: 46px;
        color: #F2F2F2;

    }

    .brief-container p {
        font-family: 'Cormorant';
        font-style: italic;
        font-weight: 300;
        font-size: 1.1em;
        line-height: 31px;
        text-align: center;
        color: #C4C4C4;
    }

    .brief-container h3 {
        font-family: 'Cormorant';
        font-style: normal;
        font-weight: 400;
        font-size: 1.3em;
        line-height: 24px;
        text-align: center;
        color: #BE9667;
        margin-top: 20px;
        margin-bottom: -20px;
    }

    .brief-container h4 {
        font-family: 'Lato';
        font-style: normal;
        font-weight: 300;
        font-size: 0.9em;
        line-height: 17px;
        text-align: center;
        color: #949494;
    }
}
</style>
