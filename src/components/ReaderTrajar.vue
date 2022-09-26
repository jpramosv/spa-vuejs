<template>
    <header class="menu">
        <nav>
            <a class="menu-logo" href="#"><img src="@/assets/logo.png" alt="logo"></a>
            <div class="mobile-menu">
                <div class="line1">cae</div>
                <div class="line1"></div>
                <div class="line1"></div>
            </div>
            <ul class="nav-list">
                <li> <a href="#">Empresa</a></li>
                <li> <a href="#">Camisaria</a></li>
                <li> <a href="#">Alfaiataria</a></li>
                <li> <a href="#">Depoimentos</a></li>
                <li> <a href="#">Contato</a></li>
            </ul>
        </nav>

    </header>
</template>

<script>
export default {
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

.menu {
    position: fixed;
    top: 0px;
    width: 100%;

}

.nav-list a:hover {
    color: #00CED1;
    transition: 1s;

}

nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    font-family: system-ui, -apple-system, Helvetica, Arial, sans-serif;
    background: linear-gradient(180deg, #000000 29.73%, rgba(0, 0, 0, 0) 100%);
    height: 8vh;
}


.nav-list {
    list-style: none;
    display: flex;
}

.nav-list li {
    letter-spacing: 3px;
    margin-left: 32px;
}

.nav-list a {
    font-family: 'Lato';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 19px;
    text-transform: uppercase;
    color: #949494;
    text-decoration: none;
}

.mobile-menu {
    display: none;
    cursor: pointer;
}

.mobile-menu div {
    width: 32px;
    height: 2px;
    background: #fff;
    margin: 8px;
    transition: 0.3s;
}

@media (max-width: 999px) {
    body {
        overflow-x: hidden;
    }

    .nav-list {
        position: absolute;
        right: 0;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;

    }

    .nav-list li {
        margin-left: 0;
        opacity: 0;
    }

    .mobile-menu {
        display: block;
    }
}

.nav-list.active {
    transform: translateX(0);
}
</style>>
 

