<script>

    export default {
        name: 'AppTitle',
        data() {
            return {
                myTitle: 'la mia prima app con Vite'
            }
        },
        methods: {
       
            }
        }
    
</script>

<template>
    <h1>{{ myTitle }}</h1>
</template>

<style scoped>
h1 {
    color: yellow;
    font-size: 5rem;
}

</style>