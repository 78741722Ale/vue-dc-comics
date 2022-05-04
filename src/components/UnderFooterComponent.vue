<template>
<!-- Quinto Componente -->
    <div class="h_under_footer w-100 bg_under_footer z_style" id="under_footer">
        <!-- Container principale -->
        <div class="container h-100">
            <div class="row m-0 w-100 h-100 d-flex justify-content-between">
                <!-- Bottone Sign-up -->
                <div class="col-2 h-100 cent">
                    <button class="p-2 ps-3 pe-3">sign-up now!</button>
                </div>
                <!-- Bottone Sign-up -->
                <div class="col-5 h-100 cent">
                    <ul class="d-flex  flex-row align-items-center gap-4 mb-0 justify-content-evenly">
                        <li><a class="text-uppercase follow" href="#">Follow Us</a></li>
                        <li><img src="@/assets/img/footer-facebook.png" alt="facebook"></li>
                        <li><img src="@/assets/img/footer-twitter.png" alt="twitter"></li>
                        <li><img src="@/assets/img/footer-youtube.png" alt="youtube"></li>
                        <li><img src="@/assets/img/footer-pinterest.png" alt="pinterest"></li>
                        <li><img src="@/assets/img/footer-periscope.png" alt="periscope"></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'UnderFooterComponent'
}
</script>


<style lang="scss" scoped>
// Link al foglio di stile
@import '@/assets/sass/partials/UnFooter.scss';

</style>

