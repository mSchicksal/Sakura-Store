<template>
    <!-- <div class="navbarCustom">
        <nav class="center">
            <ul>
                <li class="logo"><img class="logoImg" src="../../assets/img/skr_icon_green.png" /></li>
                <li> Proximamente... </li>
                <li> Proximamente... </li>
                <li> Proximamente... </li>
                <li class="btn perfil greenButtonFull"> Salir </li>
                <li class="btn perfil greenButton"> Perfil </li>
            </ul>
        </nav>
    </div> -->
    <nav class="navbar navbar-expand-sm">
        <div class="container">
            <a class="navbar-brand" href="#"><img class="logoImg" src="../../assets/img/skr_icon_green.png" /> SAKURA<strong>'STORE</strong></a>
            <ul class="navbar-nav">
                <li class="nav-item"> <a class="nav-link active-link" href="#">Inicio</a> </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Categorias
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                        <a class="dropdown-item" href="#">Categoria 1</a>
                        <a class="dropdown-item" href="#">Categoria 2</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Ver todos</a>
                    </div>
                </li>
                <li class="nav-item"> <a class="nav-link" href="#">Iniciar Sesión</a> </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: 'navBar',
        data() {
            return {
            }
        }
    }
</script>

<style>
    @import '../../assets/css/navbar.css';
</style>