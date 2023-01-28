<template>
    <div class="body">
        <div class="container-fluid">
            <template v-if="hidden == 0">
                <div class="row">
                    <div class="col-4 center" style="justify-content: center; display: flex;">
                        <productsComponent></productsComponent>
                    </div>
                    <div class="col-4 center" style="justify-content: center; display: flex;">
                        <productsComponent></productsComponent>
                    </div>
                    <div class="col-4 center" style="justify-content: center; display: flex;">
                        <productsComponent></productsComponent>
                    </div>
                </div>
            </template>
                <productsPage></productsPage>
        </div>
    </div>
</template>

<script>
    import productsComponent from  '../products/products.vue';
    import productsPage from  '../products/productPage.vue';

    export default {
        name: 'boDy',
        components: {
            productsComponent,
            productsPage
        },
        data() {
            return {
                hidden: 1
            }
        }
    }
</script>

<style>
    @import '../../assets/css/body.css';
</style>