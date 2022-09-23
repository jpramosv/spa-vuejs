<template>
    <footer>
        <div class="footer-container">
            <div>
                <img src="@/assets/logo_footer.png" alt="logo">
                <h1>CNPJ:04.487.685/0001-01</h1>
            </div>
            <h2>Copyright: 2021 © Renee Trajar - Todos os direitos reservados.</h2>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterTrajar'
}
</script>

<style>
footer {
    border-top: 1px solid #BE9667;

}

.footer-container {
    max-width: 1366px;
    margin: 30px auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
    flex-wrap: wrap;

}

footer h1 {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 21px;
    color: #BDBDBD;
}

footer h2 {
    font-family: 'Poppins';
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 21px;
    text-align: center;
    color: #4F4F4F;
}
</style>