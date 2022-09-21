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
                <div class="img-client">
                    <img src="@/assets/img.png" alt="">
                </div>
            </div>
            <div>
                <img src="@/assets/img1.png" alt="">
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
    padding-left: 50px;
    margin-top: 50px;
    background: url('@/assets/tailor.png') no-repeat center;
    background-size: cover;
}

.img-client img {
    position: relative;
    left: 80px;
    bottom: 50px;

}

.client-dep {
    display: flex;
    flex-direction: column;
    justify-content: space-around;
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
</style>