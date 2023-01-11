<template>
    <div class="body">
        <!-- Carrusel -->
        <div class="center section" style="font-weight: bolder; font-size: 40px;">
            Carrusel
        </div>
        <!-- Tarjetas de productos -->
        <div class="container-fluid">
            <div class="row">

                <div class="col-sm center">
                    <div class="card">
                        <img class="card-img-top" src="" alt="Card image cap">
                        <div class="card-body">
                            <h5 class="card-title">Card title</h5>
                            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                            <a href="#" class="btn greenButtonFull">Go somewhere</a>
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