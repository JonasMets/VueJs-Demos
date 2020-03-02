<template>
  <!-- Grid column -->
  <div class="col-lg-3 col-md-6 mb-4 d-flex align-items-stretch">
    <!-- Card -->
    <div class="card align-items-center">
      <!-- Card image -->
      <div class="view overlay">
        <!-- product image   "width:60px" -->
        <img :src="product.image" class="card-img-top" :style="product.style" alt />

        <!-- <div>{{product.style}}</div> -->
        <a>
          <div class="mask rgba-white-slight"></div>
        </a>
      </div>
      <!-- Card image -->
      <!-- Card content -->
      <div class="card-body text-center">
        <!-- Category & Title -->
        <a href class="grey-text">
          <h6>{{product.category}}</h6>
        </a>
        <h5 class="mb-3">
          <strong>
            <a href class="dark-grey-text">
              {{product.name}}
              <span class="badge badge-pill danger-color">{{product.badge}}</span>
            </a>
          </strong>
        </h5>
        <h5 class="font-weight-bold blue-text mb-0">
          <strong>{{product.price}}</strong>
        </h5>
      </div>
      <!-- Card content -->
    </div>
    <!-- Card -->
  </div>
</template>

<script>
export default {
  
  props: {
    product: {}
  }
};
</script>

<style scoped>
/* .imgsize{
  width: 
} */
</style>