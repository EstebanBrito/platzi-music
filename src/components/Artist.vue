<template>
  <li>
    <h2>
      <a :href="artist.url" target="_blank">{{ artist.name }}</a>
    </h2>
    <img :src="artist.image[1]['#text']">
  </li>
</template>

<script>
export default {
  name: 'artist',
  props: ['artist']
}
</script>

<style scoped>
li {
  display: block;
  margin: 10px 0 0;
}
</style>

