<template>
  <div class="home">
    <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../assets/OneDrive-2021-03-04/WallpaperStudio10-677.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/OneDrive-2021-03-04/WallpaperStudio10-20936.jpg" class="d-block w-100" alt="...">
    </div>
    <div class="carousel-item">
      <img src="../assets/OneDrive-2021-03-04/WallpaperStudio10-14975.jpg" class="d-block w-100" alt="...">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<img alt="Vue logo" src="../assets/logo.png">
    <HomeListing src="../assets/OneDrive-2021-03-07/1e995e4915723cdb0d238270bfa58623.jpg" title_of="title" body="This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer." timesince="00:00"/>
  </div>
  <Footer/>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Footer from '@/components/Footer.vue'
import HomeListing from '@/components/HomeListing.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Footer,
    HomeListing
  }
}
</script>
