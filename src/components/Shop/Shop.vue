<template>
  <div>
    <ShopProductList :products="products"/>
  </div>
</template>
    
<script setup lang="ts">
import type { ProductInterface } from '@/interfaces/product.interface';
import ShopProductList from './ShopProductList.vue';

defineProps<{
  products:ProductInterface[]
}>()

</script>

<style lang="scss" scoped>

</style>
    