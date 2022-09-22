<template>
    <section class="contact">
        <h1>Contato</h1>
        <div>
            <div class="contact-container">
                <div class="contact-itens">
                    <div>
                        <h1>TELEFONES</h1>
                        <h2>+55 (11) 3088-0757</h2>
                    </div>
                    <div>
                        <h1>E-Mail</h1>
                        <h2>renne@reneetrajar.com.br</h2>
                    </div>
                    <div>
                        <h1>atendimento personalizado</h1>
                        <a href="#">Clique aqui</a>
                    </div>
                </div>
                <div>
                    <form class="contact-itens">
                        <input type="text" placeholder="Nome">
                        <input type="text" placeholder="E-mail">
                        <input type="text" placeholder="Mensagem">
                        <button type="submit">Enviar</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
</template>
<script>

</script>

<style>
.contact {
    max-width: 1366px;
    margin: 0 auto;
}

.contact-container {
    display: flex;
    align-content: center;
    justify-content: center;

}

.contact-itens {
    display: flex;
    flex-direction: column;
    width: 400px;
    height: 300px;
    justify-content: space-around;
}

.contact-itens h1 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 18px;
    line-height: 22px;
    text-transform: uppercase;
    color: #1C86A4;
}

.contact-itens h2 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 150.1%;
    color: #828282;
}

.contact>h1 {
    text-align: center;
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 300;
    font-size: 38px;
    line-height: 46px;
    color: #1C86A4;

}

.contact-itens input {

    box-sizing: border-box;
    max-width: 600px;
    height: 42px;
    border: 1px solid #1C86A4;
    border-radius: 3px;
    font-size: 14px;
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    line-height: 17px;
    color: #C4C4C4;


}
</style>