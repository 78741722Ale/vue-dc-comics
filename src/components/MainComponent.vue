<template>
    <!-- Terzo Componente -->
    <div class="h_main bg_main w-100" id="site_main">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 h-100 gx-2 d-flex justify-content-evenly">
          <!-- Andrà poi iniettato tramite v-for -->
          <!-- Primo Logo -->
          <div class="col-2 h-100 d-flex justify-content-center flex-nowrap">
            <!-- Qui Logo -->
            <div class="col-3 h-100 cent">
              <img src="@/assets/img/buy-comics-digital-comics.png" alt="Digital Comics">
            </div>
            <!-- Qui Testo -->
            <div class="col-9 h-100 cent">
              <span>Digital Comics</span>
            </div>
          </div>
          <!-- Secondo Logo -->
          <div class="col-2 h-100 d-flex justify-content-center flex-nowrap">
            <!-- Qui Logo -->
            <div class="col-3 h-100 cent">
              <img src="@/assets/img/buy-comics-merchandise.png" alt="Digital merchandise">
            </div>
            <!-- Qui Testo -->
            <div class="col-9 h-100 cent">
              <span>Digital Merchandise</span>
            </div>
          </div>
          <!-- Terzo Logo -->
          <div class="col-2 h-100 d-flex justify-content-center flex-nowrap">
            <!-- Qui Logo -->
            <div class="col-3 h-100 cent">
              <img src="@/assets/img/buy-comics-subscriptions.png" alt="Digital subscriptions">
            </div>
            <!-- Qui Testo -->
            <div class="col-9 h-100 cent">
              <span>Digital Subscriptions</span>
            </div>
          </div>
          <!-- Quarto Logo -->
          <div class="col-2 h-100 d-flex justify-content-center flex-nowrap">
            <!-- Qui Logo -->
            <div class="col-3 h-100 cent">
              <img src="@/assets/img/buy-comics-shop-locator.png" alt="Digital Comics Shop Locator">
            </div>
            <!-- Qui Testo -->
            <div class="col-9 h-100 cent">
              <span>Comic Shop Locator</span>
            </div>
          </div>
          <!-- Quinto Logo -->
          <div class="col-2 h-100 d-flex justify-content-center flex-nowrap">
            <!-- Qui Logo -->
            <div class="col-3 h-100 cent">
              <img src="@/assets/img/buy-dc-power-visa.svg" alt="Digital Comics Power Visa">
            </div>
            <!-- Qui Testo -->
            <div class="col-9 h-100 cent">
              <span>Dc power visa</span>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'MainComponent'
}
</script>

<style lang="scss" scoped>
// Link al foglio di stile
@import '@/assets/sass/partials/main_comp.scss';
</style>