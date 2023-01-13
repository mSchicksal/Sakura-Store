<template>
    <div class="body">
        <!-- Carrusel -->
        <div class="center section" style="font-weight: bolder; font-size: 40px;">
            Carrusel
        </div>
        <!-- Tarjetas de productos -->
        <div class="container-fluid">
            <div class="row">

                <div class="col-3 center">
                    <div class="card">
                        <img class="card-img imgCard" src="../assets/img/producto_01.png" alt="Card image cap">
                        <div class="descuentoFlag">20%</div>
                        <div class="cardImgOverlay">
                            <h5 class="card-title">Nombre producto</h5>
                            <p class="card-text">of the card's content.</p>
                            <p class="card-price">$$$.</p>
                            <p class="card-stars">1 de 5 estrellas.</p>
                            <a class="btn greenButtonFull cardGreenButtton"> Añadir al carrito </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'boDy',
        data() {
            return {
            }
        }
    }
</script>

<style>
    @import '../assets/css/body.css';
</style>