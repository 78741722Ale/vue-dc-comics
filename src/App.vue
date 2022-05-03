<template>
  <div id="app">
    <!-- Primo Componente -->
    <div class="h_header w-100 bg-info bordo" id="site_header">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 bordo h-100 bg-danger"></div>
      </div>
    </div>
    <!-- Secondo Componente -->
    <div class="h_content bordo w-100 bg-info" id="site_content">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 bordo h-100 bg-danger">
          <h3>| Content Goes Here | </h3>
        </div>
      </div>
    </div>
    <!-- Terzo Componente -->
    <div class="h_main bordo w-100 bg-info" id="site_main">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 bordo h-100 bg-danger">
          <h3>Qui 5 Col </h3>
        </div>
      </div>
    </div>
    <!-- Quarto Componente - -->
    <div class="h_upper_footer bordo w-100 bg-info" id="upper_footer">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 bordo h-100 bg-danger">
          <h3>Qui tutto il footer superiore </h3>
        </div>
      </div>
    </div>
    <!-- Quinto Componente - Footer Inferiori -->
    <div class="h_under_footer bordo w-100 bg-info" id="under_footer">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 bordo h-100 bg-danger">
          <h3>Qui tutto il footer inferiore </h3>
        </div>
      </div>
    </div>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld
  }
}
</script>

<style lang="scss">
// Common rules 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.bordo {
  border: 2px solid black;
}
// Main container (equivale al body)
#app {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
// Qui do stile ma poi lo sposto nei componenti singoli
// Per ora diviso in region, poi da spostare in partials

/*#region Header */
.h_header {
  height: 100px;
}
/*#endregion */

/*#region Content */
.h_content {
  height: 130px;
}
/*#endregion */

/*#region Main */
.h_main {
  height: 155px;
}

/*#endregion */

/*#region Upper Footer */
.h_upper_footer {
  height: 370px;
}
/*#endregion */

/*#region Under Footer */
.h_under_footer {
  height: 100px;
}

/*#endregion */



</style>
