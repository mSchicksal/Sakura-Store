<template>
    <div class="card">
        <img class="card-img imgCard" src="../../assets/img/producto_03.jpg" alt="">
        <div class="descuentoFlag">20%</div>
        <div class="cardImgOverlay">
            <h5 class="card-title">Nombre producto</h5>
            <p class="card-text">Descripcion corta.</p>
            <p class="card-price">$60.000</p>
            <p class="card-rank">
                <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                <img src="../../assets/img/icons/starEmpty.png" style="width: 20px" />
                <img src="../../assets/img/icons/starEmpty.png" style="width: 20px" />
            </p>
            <a class="btn greenButtonFull cardGreenButtton"> Añadir al carrito </a>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'productsComponent',
        data() {
            return {
                
            }
        }
    }
</script>