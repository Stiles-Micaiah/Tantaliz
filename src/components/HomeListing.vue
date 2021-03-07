<template>
  <div id="HomeListing">
    <div class="card bg-dark text-white">
      <img :src="skl" class="card-img" alt="image unavailable">
      <div class="card-img-overlay">
        <h5 class="card-title">{{title_of}}</h5>
        <p class="card-text">{{body}}</p>
        <p class="card-text">{{timestamp}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeListing',
  props: {
    src: String,
    title_of: String,
    body: String,
    timestamp: String
  },
  skl: 'helo'
}
</script>

<style scoped>

</style>
