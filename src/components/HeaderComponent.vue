<template>
    <!-- Primo Componente -->
    <div class="h_header w-100" id="site_header">
        <!-- Container principale (ok ma non dinamico) -->
        <div class="container h-100">
            <div class="row m-0 w-100 h-100 d-flex justify-content-between">
                <!-- Logo (ok non dinamico) -->
                <div class="col-2 d-flex align-items-center">
                    <img src="../assets/img/dc-logo.png" alt="Logo DC">
                </div>
                <!-- Navbar -->
                <div class="col-8 h-100">
                    <ul class="d-flex h-100 flex-row align-items-center justify-content-evenly">
                        <li :href="item.href" v-for="item in headMenu" :key="item.id"> <a :class="item.text === 'Comics' ? 'active' : ''">{{item.text}}</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent',
    // Inserimento di Data
    data() {
      return {
        headMenu : [
          // Primo Link
          {
            id: 1,
            href:'#',
            text:'Characters' 
          },
            // Secondo Link
          {
            id: 2,
            href:'#',
            text:'Comics' 
          },
            // Terzo Link
          {
            id: 3,
            href:'#',
            text:'Movies' 
          },
            // Quarto Link
          {
            id: 4,
            href:'#',
            text:'Tv' 
          },
            // Quinto Link
          {
            id: 5,
            href:'#',
            text:'Games' 
          },
            // Sesto Link
          {
            id: 6,
            href:'#',
            text:'Collectibles' 
          },
            // Settimo Link
          {
            id: 7,
            href:'#',
            text:'Videos' 
          },
            // Ottavo Link
          {
            id: 8,
            href:'#',
            text:'Fans' 
          },
            // nono Link
          {
            id: 9,
            href:'#',
            text:'News' 
          },
          // Decimo Link
          {
            id: 10,
            href:'#',
            text:'Shop' 
          },
        ]
      }
    }
}
</script>

<style lang="scss" scoped>
// Link al foglio di stile
@import '@/assets/sass/partials/header.scss';

</style>