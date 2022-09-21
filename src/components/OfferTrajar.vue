<template>
    <section class="offer">
        <div class="offer-container">
            <div class="offer-desc">
                <h1>Condição Imperdível</h1>
                <h2>Compre hoje e garanta:</h2>
                <p>12% de desconto e pagamento em até <span>3 x sem juros;</span></p>
                <p>Até <span> 10 meses</span> para confeccionar sua roupa. Não se preocupe se suas medidas aumentaram ou
                    diminuíram,
                    estará sempre elegante;</p>
                <p>Condição muito especial por <span> tempo limitado;</span></p>
                <p>Poder presentear alguém com uma roupa de alta costura,<span> exclusiva.</span></p>
                <a class="offer-btn">Garanta essa condição especial!</a>
            </div>
            <div class="offer-img">
                <img src="@/assets/west.png" alt="">
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'OfferTrajar'
}
</script>

<style>
.offer {
    background: #264450;
}

.offer-desc {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    margin-left: 50px;

}


.offer-container {
    max-width: 1366px;
    max-height: 570px;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    padding: 30px;
}

.offer-desc h1 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 400;
    font-size: 53px;
    line-height: 64px;
    text-transform: uppercase;
    color: #BE9667;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25)
}

.offer-desc h2 {
    font-family: 'Cormorant';
    font-style: italic;
    font-weight: 400;
    font-size: 30px;
    line-height: 36px;
    color: #BE9667;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
}

.offer-desc p {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 22px;
    line-height: 26px;
    color: #949494;
}

.offer-btn {
    font-family: 'Lato';
    font-style: normal;
    text-decoration: none;
    text-align: center;
    font-size: 1.125em;
    display: block;
    width: 300px;
    padding: 15px 0;
    background: #BE9667;
    border-radius: 5px;
    color: #E5E5E5;

}

.offer-desc span {
    color: #E5E5E5;
}
</style>