<script setup>
import { ref } from 'vue'
import socksBlueImage from './assets/images/socks_blue.jpeg'
import socksGreenImage from './assets/images/socks_green.jpeg'

const product = ref('Socks')
const image = ref(socksBlueImage)

const url = ref('https://via.placeholder.com/150')

</script>

<template>
  <div class="product-display">
    <div class="product-container">
      <div class="product-image">
        <img :src="image">
      </div>
      <div class="product-url">
        <a :href="url">View Product</a>
      </div>
      <div class="product-info">
        <h1>{{ product }}</h1>
      </div>
    </div>
  </div>
</template>