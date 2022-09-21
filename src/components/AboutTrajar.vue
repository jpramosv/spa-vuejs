<template>
    <section class="about">
        <div class="about-container">
            <div class="about-img">
                <img src="@/assets/renee.png" alt="renee">
            </div>
            <div class="about-item">
                <h1>Renee Trajar</h1>
                <p>Com mais de 35 anos de experiência em camisas, calças e ternos sob medida, possuímos profissionais
                    experientes e altamente qualificados.</p>
                <p>Cada cliente tem seu molde exclusivamente desenvolvido para seu biotipo através das medidas tiradas
                    pelo próprio Sr. Renee, no escritório ou residência do cliente.</p>

                <div class="dest">
                    <p> “Nosso objetivo é superar a expectativa do cliente proporcionando-lhe satisfação ao
                        usar nossos produtos, aliado a um relacionamento franco e honesto, valorizando o ser humano.”
                    </p>

                </div>
                <a class="about-btn" href="#">Agenda uma visita!</a>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'AboutTrajar'
}
</script>
<style>
.about {
    background: #E5E5E5;
}

.about-container {
    max-width: 1366px;
    margin: 0 auto;
    display: flex;
    flex-direction: row;
    padding-top: 50px;
    padding-bottom: 50px;
    padding-left: 100px;
}

.about-item {
    max-width: 700px;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    padding-left: 100px;

}

.about-img img {
    width: 100%;
}

.about-item h1 {
    font-family: 'Cormorant';
    font-style: normal;
    font-weight: 300;
    font-size: 38px;
    line-height: 46px;
    color: #014561;

}

.about-item h1::after {
    content: '';
    display: block;
    width: 53px;
    height: 1px;
    background: #70B0C4;


}

.about-item p {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 19px;
    line-height: 141.3%;
    color: #333333;
}

.dest p {
    font-family: 'Cormorant';
    font-style: italic;
    font-weight: 400;
    font-size: 24px;
    line-height: 141.3%;
    color: #1C86A4;
}

.about-btn {
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

}

.about-btn a {
    color: #E5E5E5;
}
</style>