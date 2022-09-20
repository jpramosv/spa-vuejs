<template>
    <section class="intro">
        <div class="intro-container">
           
                <h1> ALFAIATE</h1>
          
            <h2>COMPRE HOJE, <span>PAGUE EM ATÉ 3X COM 12% DE DESCONTO</span>  E TENHA
                10 MESES PARA CONFECCIONAR!</h2>
                
                <a class="intro-btn" href="#">FAÇA UM ORÇAMENTO</a>
           
        </div>             
    </section>
</template>

<script>

export default ({
    name:'IntroTrajar'
})
</script>
<style>

.intro {
    background: url('@/assets/banner.png') no-repeat center;
    background-size: cover;      
    color: #fff;
}

.intro-container{
    max-width: 1366px;
    height: 630px;
    margin: 0 auto; 
    display: flex;
    flex-direction: column;
        
    }

.intro h1{
    width: 404.18px;
    height: 119.58px;  
    font-family: 'Playfair Display';
    font-style: normal;
    font-weight: 400;
    font-size: 5.5em;
    line-height: 120px;
    color: rgba(2, 75, 104, 0.68);
    margin-top: 150px;
        
}
.intro h1::before{
    content:'Elegante é ter um';
    display: block;
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-size: 32.5627px;
    line-height: 43px;
    color: #BE9667;
}

.intro h1::after{
    content:'para chamar de seu.';
    display: block;  
    font-family: 'Playfair Display';
    font-style: italic;
    font-weight: 400;
    font-size: 32.5627px;
    line-height: 43px;
    color: #BE9667; 
    padding-left: 135px;   
}

.intro h2{
    margin-top: 150px;    
    max-width: 438px;
    max-height: 93px;   
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 24px;
    line-height: 131%;    
    text-transform: uppercase;
    color: #949494;     
}

.intro span{
    color: #fff; 
}
.intro-btn{     
    font-family: 'Lato';
    font-style: normal;
	text-decoration: none;
	text-align: center;
	font-size: 1.125em;	
	text-transform: uppercase;
	display: block;
	width: 300px;
	padding: 15px 0;	
    background: #014561;
    border-radius: 5px;
    color: #E5E5E5;
    margin-top: 20px;
}
.intro-btn a{
    color: #E5E5E5;
}
</style>
