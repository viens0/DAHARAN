<template>
  <div class="hero">
    <!-- dekstop -->
    <div class="d-none d-md-block">
      <div class="row mt-5">
        <div class="col-md-6">
          <div class="d-flex h100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Menu Makanan Yang paling lezat, </strong> <br />
                murah meriah
              </h2>
              <p>Ayo Segerah pesan makanan faforit anda sebelum kehabisan</p>
              <router-link class="btn btn-lg btn-success" to="/Foods">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/Hero.svg" width="100%" />
        </div>
      </div>
    </div>

    <!-- mobile -->
    <div class="d-sm-block d-md-none">
      <div class="row mt-5">
        <div class="col-md-6 mb-3">
          <img src="../assets/Hero.svg" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>Menu Makanan Yang paling lezat, </strong> <br />
                murah meriah
              </h2>
              <p>Ayo Segerah pesan makanan faforit anda sebelum kehabisan</p>
              <button class="btn btn-lg btn-success">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>
justify-content-center.align-self-center
<style>
</style>