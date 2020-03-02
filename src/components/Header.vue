<template>
  <div class="">
    <!-- myNavbarColor indigo fixed-top position-fixed -->
    <nav class="navbar  fixed-top navbar-expand-lg navbar-dark myNavbarColor">
      
      <div class="container">

        <router-link to="/" class="navbar-brand">
          <img src="../../public/images/logoskiname8.svg" alt />
        </router-link>

        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarTogglerDemo02"
          aria-controls="navbarTogglerDemo02"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarTogglerDemo02">
          <!-- mr-auto -->
          <ul class="navbar-nav ml-auto mt-lg-0">
            <li class="nav-item">
              <router-link to="/" class="nav-link">Home</router-link>
            </li>
            <li class="nav-item">
              <!-- <a class="nav-link" href="#">Link</a> -->
              <router-link to="/about" class="nav-link">About</router-link>
            </li>

            <li class="nav-item">
              <!-- <a class="nav-link" href="#">Link</a> -->
              <router-link to="/products" class="nav-link">Products</router-link>
            </li>
          </ul>
        </div>

      </div>

    </nav>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.navbar-brand {
  width: 160px;
}
</style>