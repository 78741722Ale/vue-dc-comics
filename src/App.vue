<template>
  <div id="app">
    <!-- Primo Componente -->
    <HeaderComponent />
    <!-- Jumbotron -->
    <JumboComponent />
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
import JumboComponent from '@/components/JumboComponent.vue'
import ContentComponent from '@/components/ContentComponent.vue'
import MainComponent from '@/components/MainComponent.vue'
import UpperFooterComponent from '@/components/UpperFooterComponent.vue'
import UnderFooterComponent from '@/components/UnderFooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    JumboComponent,
    ContentComponent,
    MainComponent,
    UpperFooterComponent,
    UnderFooterComponent
  }
}
</script>

<style lang="scss">

// importazione del file style.scss
@import "@/assets/sass/style.scss" ;

</style>
