<template>
    <section class="products">
        <div class="products-container">
            <div class="camisaria-img">
                <img src="@/assets/camisaria.png" alt="">
            </div>
            <div class="camisaria-text">
                <h1>Camisaria</h1>
                <h2>Confeccionadas artesanalmente</h2>
                <ul>
                    <li>100% Algodão</li>
                    <li>Monograma</li>
                    <li>Slim</li>
                    <li>Nacionais e Importadas</li>
                    <li>Tradicionais e Esportivas</li>
                    <li>Casamentos</li>
                </ul>
                <a class="products-btn" href="#">Quero orçamento</a>
            </div>
        </div>
        <div class="products-container">
            <div class="camisaria-text camisaria-left">
                <h1>Camisaria</h1>
                <h2>Confeccionadas artesanalmente</h2>
                <ul>
                    <li>100% Algodão</li>
                    <li>Monograma</li>
                    <li>Slim</li>
                    <li>Nacionais e Importadas</li>
                    <li>Tradicionais e Esportivas</li>
                    <li>Casamentos</li>
                </ul>
                <a class="products-btn" href="#">Quero orçamento</a>
            </div>
            <div class="camisaria-img">
                <img src="@/assets/camisaria.png" alt="">
            </div>

        </div>
    </section>
</template>

<script>
export default {
    name: 'ProductsTrajar'
}
</script>

<style>
.products-container {
    max-width: 1366px;
    margin: 0 auto;
    display: flex;
    padding-left: 50px;
    padding-top: 100px;
    align-items: center;
    flex-wrap: wrap;
}

.camisaria-img {
    max-width: 550px;
}

.camisaria-img img {
    width: 90%;
}

.camisaria-img {

    margin: 20px auto;
    padding-right: -80px;
    border: 7px solid white;
    box-shadow: 0 0 0 1px #1C86A4;

}

.camisaria-text {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 700px;
    height: 400px;
    justify-content: center;
    margin-right: 100px;
    border-top: 1px solid #E5E5E5;
    border-right: 1px solid #E5E5E5;
    border-bottom: 1px solid #E5E5E5;

}

.camisaria-left {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 400px;
    width: 700px;
    justify-content: center;
    margin-right: 80px;
    border-top: 1px solid #E5E5E5;
    border-right: 0px solid #E5E5E5;
    border-left: 1px solid #E5E5E5;
    border-bottom: 1px solid #E5E5E5;

}

.camisaria-text ul {
    columns: 2;
    padding-top: 40px;
    padding-left: -30px;
}

.camisaria-text li {
    font-family: 'Cormorant';
    font-style: italic;
    font-weight: 400;
    font-size: 24px;
    line-height: 29px;
    color: #727272;
}

.camisaria-text h1 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 300;
    font-size: 62px;
    line-height: 75px;
    text-transform: uppercase;
    color: #014561;
}

.camisaria-text h2 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 19px;
    text-transform: uppercase;
    color: #C4C4C4;
}

.products-btn {
    font-family: 'Lato';
    font-style: normal;
    text-decoration: none;
    text-align: center;
    font-size: 1.125em;
    display: block;
    width: 300px;
    padding: 15px 0;
    background: #014561;
    border-radius: 5px;
    color: #E5E5E5;
    margin-top: 15px;

}

.products-btn a {
    color: #E5E5E5;
}
</style>