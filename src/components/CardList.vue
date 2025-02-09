<template>
  <div class="row mt-4 gy-4">
    <div class="col-md-3" v-for="card in cards" :key="card.title">
      <div class="card rounded-2 h-100">
        <img
          :src="card.imageSrc"
          class="card-img-top rounded-2"
          :alt="card.title"
        />
        <div class="card-body">
          <p class="card-text">{{ card.title }}</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
    const props = defineProps({
        cards
    })
</script>

<style scoped></style>
