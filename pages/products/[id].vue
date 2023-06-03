<template>
  <div>
    <p>Product details for {{ id }}</p>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio id voluptatem quod et tempora odit nesciunt
      nisi, iusto, rerum ipsum nemo! Natus ea a voluptates accusamus voluptate, adipisci quia qui.</p>
  </div>
</template>

<script setup>
const { id } = useRoute().params
definePageMeta({
  layout: 'products'
})
</script>

<style scoped></style>