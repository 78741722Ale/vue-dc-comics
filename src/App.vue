<template>
  <div id="app">
    <!-- Primo Componente -->
    <HeaderComponent />
    <!-- Secondo Componente -->
    <ContentComponent />
    <!-- Terzo Componente -->
    <MainComponent />
    <!-- Quarto Componente - -->
    <UpperFooterComponent />
    <!-- Quinto Componente -->
    <UnderFooterComponent />
  </div>
</template>

<script>
import HeaderComponent from '@/components/HeaderComponent.vue'
import ContentComponent from '@/components/ContentComponent.vue'
import MainComponent from '@/components/MainComponent.vue'
import UpperFooterComponent from '@/components/UpperFooterComponent.vue'
import UnderFooterComponent from '@/components/UnderFooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    ContentComponent,
    MainComponent,
    UpperFooterComponent,
    UnderFooterComponent
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
  width: 100vw;
  height: 1000px;
}
// Qui do stile ma poi lo sposto nei componenti singoli
// Per ora diviso in region, poi da spostare in partials

/*#region Upper Footer */
.h_upper_footer {
    height: calc(100% - 50%);
}
/*#endregion */



</style>
