<template>
    <div class="container productPage">
        <div class="row" style="border: 1px solid red;">
            <div class="col-6" style="border: 1px solid red;">
                <div class="center">
                    <img class="productImg" src="../../assets/img/producto_03.jpg" alt="Card image cap">
                </div>
            </div>
            <div class="col-6 center" style="border: 1px solid red;">
                <div class="row">
                    <div class="titulo">
                        <p>Titulo del producto</p>
                    </div>
                    <div class="price">
                        <p>$60.000</p>
                    </div>
                    <div class="stars">
                        <p>
                            <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                            <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                            <img src="../../assets/img/icons/starFull.png" style="width: 20px" />
                            <img src="../../assets/img/icons/starEmpty.png" style="width: 20px" />
                            <img src="../../assets/img/icons/starEmpty.png" style="width: 20px" />
                        </p>
                    </div>
                    <div class="descr">
                        <p>
                            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptatem, fugit quam in enim natus pariatur esse veritatis consequuntur delectus! Optio officia magnam fugiat. Similique eaque sunt accusantium repudiandae, eum esse!
                        </p>
                    </div>
                    <div>
                        <a class="btn btnProduct"> Añadir al carrito </a>
                    </div>
                </div>
                <div class="row" style="border: 1px solid red;">
                    <div class="detail">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'productsPage',
        data() {
            return {
                
            }   
        }
    }
</script>

<style>
        @import '../../assets/css/productPage.css';
</style>