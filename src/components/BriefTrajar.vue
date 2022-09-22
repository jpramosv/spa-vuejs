<template>
    <section class="brief">
        <div class="brief-container">
            <h1> Depoimentos</h1>
            <img src="@/assets/will.png" alt="will">
            <div class="seta">
                <p>“Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por intermédio de meu pai, que já
                    tem
                    uma história de décadas com o querido Renee.</p>
                <p>O excelente atendimento antes e pós venda e a alta qualidade dos materiais usados colocam a Renee
                    Trajar
                    em um patamar acima dos demais do ramo.”</p>
            </div>

            <h3>William H. M. Garey</h3>
            <h4>Advogado | Nelson Garey Advogados Associados</h4>

        </div>
    </section>
</template>
<script>

export default {
    name: 'BriefTrajar'
}

</script>


<style>
.brief {
    background: #264450;
}

.brief-container {
    max-width: 764px;
    max-height: 608px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    align-content: space-between;
    padding: 30px;
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
    font-size: 38px;
    line-height: 46px;
    height: 46px;
    color: #F2F2F2;

}

.brief-container h3 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 400;
    font-size: 20px;
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
</style>
