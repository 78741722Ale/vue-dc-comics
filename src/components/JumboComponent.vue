<template>
    <div class="h_jumbo w-100" id="site_jumbo"></div>
</template>

<script>
export default {
    name: 'JumboComponent',
}
</script>

<style lang="scss" scoped>

// Altezza del jumbotron
.h_jumbo {
    height: 450px;
}

#site_jumbo {
    background-image: url("@/assets/img/jumbotron.jpg");
    width: 100%;
    background-position: top center;
    background-size: 100% 250%;
    background-repeat: no-repeat;
    overflow-x:hidden;
    overflow-y: hidden;
}

</style>
