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
                        <a class="contact-btn" href="#">Clique aqui!</a>
                    </div>
                </div>
                <form class="contact-itens">

                    <input type="text" placeholder="Nome">

                    <input type="text" placeholder="E-mail">

                    <input class="msg" type="text" placeholder="Mensagem">


                    <button class="btn-submit" type="submit">Enviar</button>
                </form>
            </div>
        </div>
    </section>
</template>
<script>

</script>

<style>
.contact {
    max-width: 1366px;
    margin: 30px auto;
}

.contact-container {
    display: flex;
    align-content: center;
    justify-content: center;
    flex-wrap: wrap;

}

.contact-itens {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin: 30px 0;
    min-height: 300px;
    padding: 30px;
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
    min-width: 600px;
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

input:nth-child(3) {
    height: 80px;
}


.btn-submit {
    background: yellow;
}


.btn-submit {
    font-family: 'Lato';
    font-style: normal;
    text-decoration: none;
    text-align: center;
    font-size: 1.125em;
    display: block;
    min-width: 600px;
    height: 50px;
    padding: 15px 0;
    background: #014561;
    border-radius: 5px;
    color: #E5E5E5;
    margin-top: 15px;

}

.btn-submit a {
    color: #E5E5E5;
}

.contact-btn {
    font-family: 'Lato';
    font-style: normal;
    text-decoration: none;
    font-size: 1.125em;
    width: 270px;
    height: 50px;
    color: #014561;
    background: white;
    border: 1px solid #1C86A4;
    border-radius: 2px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
}

@media(max-width:764px) {

    .contact-itens input {

        min-width: 300px;


    }


    .btn-submit {
        min-width: 300px;

    }

    .btn-submit a {
        color: #E5E5E5;
    }

    .contact-itens {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        margin: 10px 0;
        min-height: 300px;
        padding: 30px;
    }


}
</style>