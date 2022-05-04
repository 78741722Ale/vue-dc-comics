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
// Altezza fissa dell'header
.h_header {
    height: 10%;
}

// Background Header
.bg_header {
    background-color: #FFFFFF;
}

// Dimensioni del logo
.col-2 {
    // Annidamento
    img {
        width: 75px;
        height: 75px;
    }
}

// Colonna Navbar
.col-8 {
    // Annidamento
    ul {
        list-style: none;
    }
    li {
        padding-left: 0;
        margin-bottom: 0;
        
    }

    a {
        text-decoration: none;
        text-transform: uppercase;
        color: inherit;
        font-size: 0.8rem;
        padding-bottom: 2.3rem;
    }

    a:hover {
        border-bottom: 5px solid rgb(0, 213, 246);
        color: rgb(0, 213, 246);
    }


    .active {
        border-bottom: 5px solid rgb(0, 213, 246);
        color: rgb(0, 213, 246);
    }


}

</style>