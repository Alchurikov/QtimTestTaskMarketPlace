<template>
  <div class="bg-white">
    <Header />
    <main
      class="mx-auto max-w-2xl px-4 pb-24 pt-16 sm:px-6 lg:max-w-7xl lg:px-8"
    >
      <h1 class="text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl">
        Shopping Cart
      </h1>

      <form
        class="mt-12 lg:grid lg:grid-cols-12 lg:items-start lg:gap-x-12 xl:gap-x-16"
      >
        <CartItemList />
        <CartOrderSummary />
      </form>
    </main>
  </div>
</template>

<script setup lang="ts">
import CartItemList from '../components/Cart/CartItemList.vue';
import CartOrderSummary from '../components/Cart/CartOrderSummary.vue';
</script>
