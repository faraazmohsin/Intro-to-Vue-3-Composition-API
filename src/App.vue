<script setup>
import { ref } from 'vue'

const product = ref('Socks')

const description = ref('This is a pair of blue socks.')
</script>

<template>
  <div class="product-display">
    <div class="product-container">
      <div class="product-info">
        <h1>{{ product }}</h1>
        <p>{{ description }}</p>
      </div>
    </div>
  </div>
</template>