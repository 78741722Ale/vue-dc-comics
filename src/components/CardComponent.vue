<template>
    <!-- Card -->
    <div class="col-2 bg-danger card_item">
        <img :src="image" alt="title">
        <h5>{{bigText}}</h5>
    </div>
</template>

<script>
export default {
    // Nome del componente
    name: 'CardComponent',
    props: {
        // Equivale a thumb dell'elemento padre
        image: String,
        // Equivale a series dell'elemento padre
        bigText: String
    }
}
</script>

<style lang="scss" scoped>
// Link al foglio di stile
@import '@/assets/sass/partials/component.scss';

</style>