<template>
    <footer>
        <p>&copy; 2021 by Unknown</p>
        <router-link to="/about">About</router-link>
    </footer>
</template>

<script>
    export default {
        name: 'Footer',
    }
</script>

<style scoped>
    a {
        color: #333;
    }

    footer {
        margin-top: 30px;
        text-align: center;
    }
</style>