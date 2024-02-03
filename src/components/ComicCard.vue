<script>
export default {
  name: 'ComicCard',
  props: {
    thumb: String,
    title: String
  }
}
</script>
<template>
  <div class="card">
    <img :src="thumb" :alt="title + 'image'" />
    <h5>{{ title }}</h5>
  </div>
</template>

<style scoped>
.card
{
  & > img
  {
    aspect-ratio: 1;
    object-fit: cover;
    object-position: top;
  }
}
</style>