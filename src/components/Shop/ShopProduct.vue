<script setup lang="ts">

</script>

<template>
    <div class="product d-flex flex-column">
        <div class="product-image"></div>
        <div class="p-10 d-flex flex-column">
            <h4>MacBoobk Pro</h4>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolores dignissimos doloribus pariatur ad nam temporibus praesentium.</p>
            <div class="d-flex flex-row align-items-center">
                <span class="flex-fill">Prix : 1500$</span>
                <button class="btn btn-primary">Ajuter au panier</button>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>
    .product {
        background-color: #ffff;
        border: var(--border);
        border-radius: var(--border-radius);
        &-image {
            border-top-right-radius: var(--border-radius);
            border-top-left-radius: var(--border-radius) ;
            background-image: url(../../assets/mac.png);
            background-size: cover;
            background-position: center;
            height: 250px;
        }

    }
</style>