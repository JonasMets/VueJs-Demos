<template>
  <div class="home">
    <!-- Jumbotron  https://mdbootstrap.com/img/Photos/Others/forest2.jpg-->
    <!-- style="background-image: url(../../public/images/snowforest1.jpg) center;" -->
    <div class="card card-image">
      <div class="text-white text-center rgba-stylish-strong py-5 px-4">
        <div class="py-5">
          <!-- Content -->
          <!-- <h5 class="h5 orange-text">
            <i class="fas fa-camera-retro"></i> Photography
          </h5>-->
          <h2 class="card-title h2 my-4 py-2">Jumbotron with image overlay</h2>
          <!-- <p
            class="mb-4 pb-2 px-md-5 mx-md-5"
          >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur obcaecati vero aliquid libero doloribus ad, unde tempora maiores, ullam, modi qui quidem minima debitis perferendis vitae cumque et quo impedit.</p> -->
          <!-- <a class="btn peach-gradient">
            <i class="fas fa-clone left"></i> View project

          </a>-->
        </div>
      </div>
    </div>
    <!-- Jumbotron -->

    <div id="ourPhilosophy" class="container">
      <h1>Our Philosophy</h1>
      <p>Our skis is about that second relationship where you do everything better. Much better.  We knew there was much more that could be done to ski design. With this new ski we explore many of the ideas that never fit into a established category in the industry.  We make the great skis for freeriding. Everywhere. With the least impact on nature.  We believe in equality. We don't make skis for men. We don't make skis for women.</p>
      <p>We make skis for skiers.</p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'


export default {
  name: "Home",
  components: {
    // HelloWorld
  }
};
</script>

<style scoped>
.card-image {
  /* ../../public/images/snowforest1.jpg) center */
  background-image: url("../../public/images/snowforest1.jpg");
  position: relative;
}

#ourPhilosophy h1 {
  margin-top: 2rem;
}

</style>
