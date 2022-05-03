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
                        <li><a href="#">CHARACTERS</a></li>
                        <li><a href="#">COMICS</a></li> 
                        <li><a href="#">MOVIES</a></li>
                        <li><a href="#">TV</a></li>
                        <li><a href="#">GAMES</a></li> 
                        <li><a href="#">COLLECTIBLES</a></li>
                        <li><a href="#">VIDEOS</a></li> 
                        <li><a href="#">FANS</a></li>
                        <li><a href="#">NEWS</a></li>
                        <li><a href="#">SHOP</a></li> 
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderComponent'
}
</script>

<style lang="scss" scoped>
// Altezza fissa dell'header
.h_header {
    height: 100px;
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
        // border-bottom: 1px solid black;
    }
    a {
        text-decoration: none;
        color: inherit;
        font-size: 0.8rem;
    }
}





</style>