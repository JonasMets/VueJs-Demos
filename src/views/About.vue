<template>
  <div class="container">
  <!-- <h1>About Our Company</h1> -->
  <div id="aboutUs" class="aboutUs-content">
    <img class="aboutUs-image1" src="images/person-skiing-3.jpg" alt="">
    <div class="aboutUs-text w-responsive mx-auto mb-5">
      <h2 class=""> We love skis </h2>
      <p> Together with a few friends we are Thor Skis. For five years we lived in Verbier, Switzerland designing all skis for Faction Skis and the legendary skier Candide Thovex. With my skis I’ve won most magazine ski tests there is.  We’re based in Torshälla, Sweden and we produce our skis in one of the best ski factories in the world. As close as it gets from all suppliers.  We only work with the best. Atomic supply us with bindings such as the Warden MNC 13, Shift MNC 13, STH2 16, and Backland Tour. On the way up we use Pomoca glueless skins.Enjoy! </p>
    </div>
  </div>
</div>
</template>

<script>
export default {
  
}
</script>

<style scoped>
#aboutUs .aboutUs-image1 {
    /* width: 50%;
    height: auto; */
    display: none;
  }

  .aboutUs-content {
    display: flex;
  }

  .aboutUs-text h2 {
    margin-bottom: .5rem;
  }

  .aboutUs-text {
    /* justify-content: center; */
    align-self: center;
    padding: 2rem;
    margin-bottom: 10rem;
  }

@media(min-width:560px) {
    #aboutUs .aboutUs-image1 {
      display: flex;
      border: none;
      /* flex: 1; */
      width: 50%;
      /* height: auto; */
      min-height: 700px;
      /* overflow: hidden; */
      
    }

    .aboutUs-content {
      display: flex;
    }

    .aboutUs-text h2 {
      margin-bottom: .5rem;
    }

    .aboutUs-text {
      /* justify-content: center; */
      align-self: center;
      padding: 2rem;
    }

  }
</style>
