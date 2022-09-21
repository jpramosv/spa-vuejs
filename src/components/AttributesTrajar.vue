<template>
    <section class="attr">
        <div class="attr-item">
            <img src="@/assets/Vector-1.png" alt="maq">
            <h1>Qualidade</h1>
            <h2>Camisaria e Alfaiataria 100% artesanal.</h2>
        </div>
        <div class="attr-item quotes">
            <img src="@/assets/medal.png" alt="maq">
            <h1>Confiança</h1>
            <h2>Atendimento personalizado no escritório ou residência.</h2>
        </div>
        <div class="attr-item">
            <img src="@/assets/exp.png" alt="maq">
            <h1>Experiência</h1>
            <h2>Tradição e modernidade proporcionando elegância.</h2>
        </div>

    </section>
</template>
<script>
export default {
    name: 'AttributesTrajar'
}
</script>

<style>
.attr {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    max-width: 1366px;
    height: 150px;
    margin: 0 auto;
    justify-content: space-around;
    align-items: center;

}

.attr-item {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.attr-item img {
    width: 37px;
}

.attr-item h1 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 600;
    font-size: 24px;
    line-height: 29px;
    text-transform: uppercase;
    color: #1C86A4;
    padding: 10px;
}

.attr-item h2 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 17px;
    text-align: center;
    color: #727272;
}

.quotes {
    border-right: 1px solid #CCCCCC;
    border-left: 1px solid #CCCCCC;
    padding: 20px;
    height: 50px;
    justify-content: center;
}
</style>