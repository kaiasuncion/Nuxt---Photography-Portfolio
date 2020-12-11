<template>
  <div class="wrapper">
    <img
      v-for="data in imageData"
      :key="data.id"
      :class="data.categories"
      :src="require(`~/assets/photos/${data.path.regular}`)"
      :alt="data.alt_description"
    />
  </div>
</template>

<script>
import photoData from './photoData.json'

export default {
  data() {
    return {
      imageData: photoData,
    }
  },
}
</script>

<style scoped>
.wrapper {
  margin: 0 auto;
  width: 100%;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-between;
}
img {
  margin: 0 auto;
  padding: 5px;
  transition: 0.3s ease-in-out;
  width: 50%;
  max-height: auto;
  object-fit: cover;
}
.panorama {
  max-width: 100%;
  width: 100%;
}
</style>
