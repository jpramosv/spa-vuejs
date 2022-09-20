<template>
    <header class="menu">
        <div class="menu-container">
            <a class="menu-logo" href="#"><img src="@/assets/logo.png" alt="logo"></a>
           
            <nav class="menu-nav">
                <ul>
                    <li> <a href="#">Empresa</a></li>
                    <li> <a href="#">Camisaria</a></li>
                    <li> <a href="#">Alfaiataria</a></li>
                    <li> <a href="#">Depoimentos</a></li>
                    <li> <a href="#">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
    export default{
        name: 'ReaderTrajar'
    }
</script>
<style>
   /* Reset */
body,
h1,
h2,
h3,
p,
ul {
    padding: 0px;
    margin: 0px;
}

body {
    font-family: Georgia, 'Times New Roman', Times, serif;
    color: #252525;
}
.menu{
    position: fixed;
    left: 0;
    top: 0;
    width: 100%;  
    
}
.menu-container{
    max-width: 1366px;
    max-height: 111px;
    margin: 0 auto;
    background: linear-gradient(180deg, #000000 29.73%, rgba(0, 0, 0, 0) 100%);
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-top: 20px;
    padding-left:50px;
    
}

.menu-nav li{
    display: inline-block;
}
.menu-nav a{
    display: block;
    padding: 10px;
    text-decoration: none;
    color: #fff;
    font-size: 1.125em;
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 19px;
    text-transform: uppercase;
    color: #949494;

}

</style>>
 

