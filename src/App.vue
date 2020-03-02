<template>
  <div id="app">
    
    <myHeader/>

    <router-view class="router-view-padding-top"/>

    <myFooter />

  </div>
</template>

<script>
import myHeader from "./components/Header";
import myFooter from "./components/Footer";

export default {
  components: {
    // HelloWorld
    myHeader,
    myFooter
  }
};
</script>


<style>
:root{
  --primaryColor:#505C77;
  --primaryColorDarker:#384a74;
  --primaryBackground:#E1E1E1;
  --navbarText:#F9FAFC;
  --footerText:#F9FAFC;
  --black:#000;
  --black-faded:#1b1b1b;
  --darkGrey: #333;
  --mediumGrey: #444;
  --lightGray: #cfcfcf;
  --white: #fff;
  --boneWhite:#F9FAFC;
  --boxShadowPrimaryD: #505C77;
  --boxShadowGrey: rgba(68, 68,68, .5);
}

.myNavbarColor{
  background-color: var(--primaryColor);
}


#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color:var(--primaryColorDarker);
}

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
.nav-link.router-link-exact-active {
  /* color: #42b983; */
  background-color: var(--boxShadowGrey);
}

.navbar-margin-bottom{
  margin-bottom: 3rem;
}

.router-view-margin-top{
margin-top: 60px;
}
.router-view-padding-top{
padding-top: 50px;
}

/* .navbar-brand {
  width: 160px;
} */

</style>
