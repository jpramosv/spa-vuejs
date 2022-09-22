<template>
    <section class="client">
        <div class="client-container">
            <div class="item-client">
                <div class="client-dep">
                    <h2>“Faço roupas com o Renee Trajar há mais de duas décadas, o serviço é impecável em todos os
                        detalhes, desde a costura ao caimento. O Renee tem uma equipe de mestre!”</h2>
                    <div class="nelson">
                        <h2>Nelson Garey</h2>
                        <h3>Advogado | Nelson Garey Advogados Associados</h3>
                    </div>

                </div>

            </div>

            <div class="img-client-cont">
                <img class="img-client" src="@/assets/img.png" alt="">
                <img class="img-client1" src="@/assets/img1.png" alt="">
            </div>

        </div>

    </section>
</template>

<script>
export default {
    name: 'ClienteTrajar'
}
</script>

<style>
.client {
    background: #EFF7F9;
}

.client-container {
    max-width: 1366px;
    display: flex;
    margin: 0 auto;

}

.item-client {
    display: flex;
    max-width: 600px;
    padding-left: 50px;
    margin-top: 50px;
    background: url('@/assets/tailor.png') no-repeat center;
    background-size: cover;
}

.img-client {
    margin-right: -50px;
    z-index: 1;
}

.img-client1 {
    z-index: 1;
}

.client-dep {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    max-width: 500px;
}

.client-dep>h2 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 24px;
    line-height: 141.3%;
    text-align: center;
    color: #828282;
}

.nelson h2 {
    font-family: 'Cormorant';
    font-style: italic;
    font-weight: 400;
    font-size: 28px;
    line-height: 141.3%;
    text-align: center;
    color: #014561;
}

.nelson h3 {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 141.3%;
    text-align: center;
    color: #BE9667;
}

@media (max-width: 999px) {
    .client-container {
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
    }

    .img-client-cont img {
        width: 50%;
    }
}
</style>