<template>
    <!-- Secondo Componente -->
    <div class="h_content w-100 bg_content" id="site_content">
        <!-- Container principale -->
        <div class="container h-100">
            <div class="row m-0 w-100 h-100">
                <div class="col-3 d-flex justify-content-start align-items-center">
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

// Background
.bg_content {
    background-color: #1C1C1C;
}


/*#endregion */



</style>