<template>
    <img src="./static/home.png" width="50" height="50"/>
    <h1>Minimal Vue Webpack</h1>
</template>

<script>

import { defineComponent } from 'vue'; 

export default defineComponent({
    name: 'App'
});

</script>

<style scoped>
    h1 {
        width: 100%;
        text-align: center;
        margin-top: 10px;
    }

    img {
        display: block;
        margin: auto;
    }
</style>