<template>
    <!-- Secondo Componente -->
    <div class="h_content w-100 bg_content" id="site_content">
        <!-- Container principale -->
        <div class="container rel h-100">
            <div class="row m-0 w-100 h-100">
                <div class="col-3 d-flex justify-content-start align-items-center">
                    <!-- Banner -->
                    <span class="abs banner">Current Series</span>
                    
                    <h3> --| Content Goes Here |-- </h3>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ContentComponent'
}
</script>


<style lang="scss" scoped>

/*#region Content */
.h_content {
    height: 15%;
}

// Colonna iniziale di contenimento
.col-3 {
    // Annidamento
    h3 {
        font-weight: bold;
        font-size: 1.4rem;
        margin-bottom: 0rem;
        color: white;
    }
}

// Position
.rel {
    position: relative;
}
.abs {
    position: absolute;
    top: 0%;
    transform: translate(0%, -50%);
}

.banner {
    text-decoration: none;
    color: white;
    text-transform: uppercase;
    font-size: 1.7rem;
    font-weight: 900;
    background-color: #0282F9;
    padding:5px 20px 5px 20px
}


// Background
.bg_content {
    background-color: #1C1C1C;
}

</style>