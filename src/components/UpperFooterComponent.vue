<template>
<!-- Quarto Componente -->
    <div class="h_upper_footer w-100" id="upper_footer">
      <!-- Container principale -->
      <div class="container h-100">
        <div class="row m-0 w-100 h-100 d-flex justify-content-between align-items-center">
          <!-- Lista del footer (ok ma non dinamica) -->
          <div class="col-6 d-flex h_80">
            <!-- Prima lista (ok ma non dinamica) -->
            <div class="col-4 d-flex flex-wrap flex-column">
              <!-- upper -->
              <div class="pt-2 ps-2 w-100 h_70">
                <h4 v-html="title_1" class="t-left list_title">{{title_1}}</h4>
                <ul class="t-left">
                  <li v-for="element in first_element" :key="element">{{element}}</li>
                </ul>
              </div> 
              <!-- under list -->
              <div class="ps-2 w-100 h_30">
                <h4 v-html="title_2" class="t-left list_title">{{title_2}}</h4>
                <ul class="t-left">
                  <li v-for="element in second_element" :key="element">{{element}}</li>
                </ul>
              </div> 
            </div>
            <!-- Seconda lista -->
            <div class="col-4">
              <!-- DC list -->
              <div class="pt-2 ps-2 w-100 h-100">
                <h4 v-html="title_3" class="t-left list_title">{{title_3}}</h4>
                <ul class="t-left">
                  <li v-for="element in third_element" :key="element">{{element}}</li>
                </ul>
              </div> 
            </div>
            <!-- Terza lista -->
            <div class="col-4">
              <!-- Sites -->
              <div class="pt-2 ps-2 w-100 h-100">
                <h4 v-html="title_4" class="t-left list_title">{{title_4}}</h4>
                <ul class="t-left">
                  <li v-for="element in fourth_element" :key="element">{{element}}</li>
                </ul>
              </div>     
            </div>
          </div>
          <!-- Logo Dc -->
          <div class="col-5 dc_logo h-100 d-flex justify-content-center align-items-center">
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
    name: 'UpperFooterComponent',
    data() {
      return {
        // DC Comics
        title_1: 'Dc Comics',
        first_element: ['Characters', 'Comics', 'Movies', 'Tv', 'Games', 'Videos', 'News'],
        // Shop
        title_2: 'Shop',
        second_element: ['Shop DC', 'Shop DC Collectibles'],
        // DC & Therm of Use
        title_3: 'DC',
        third_element: [
          'Terms Of Use', 
          'Privacy policy (New)', 
          'Ad Choices',
          'Advertising',
          'Jobs',
          'Subscriptions',
          'Talent Workshops',
          'CPSC Certificates',
          'Ratings',
          'Shop Help',
          'Contact us',
          ],
        title_4: 'Sites',
        fourth_element: ['DC','MAD Magazine','DC Kids','DC Universe','DC Power Visa' ]
      }
    }
}

</script>

<style lang="scss" scoped>
// Link al foglio di stile
@import '@/assets/sass/partials/UpFooter.scss';
</style>
