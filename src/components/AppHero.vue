<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppHero',
        components: {
          AppTitle,
        }
  }
    
</script>

<template>
    <div class="hero">
        <AppTitle></AppTitle>
    </div>
    
</template>

<style scoped>
    .hero {
        background-image: url(../assets/StrikeApp.png);
        background-size: cover;
        background-position: center;
        color: #ffffff;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 1000px;
        height: 700px;
        margin: auto;
    }
</style>