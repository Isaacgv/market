<script setup lang="ts">
    import ShopProduct from './ShopProduct.vue';
</script>

<template>
    <div class="grid">
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
        <ShopProduct />
    </div>

</template>

<style lang="scss" scoped>

    .grid {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-template-rows: 300px;
        grid-auto-rows: 300px;
        gap: 20px;
    }

</style>
