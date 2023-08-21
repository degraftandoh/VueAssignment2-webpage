<script setup>
    defineProps(["image", "socialText"]);
</script>

<template>
    <div class="social">
        <img :src="image" />
        <p>{{ socialText }}</p>
        <img src="../assets/Group 1.1.svg" />
    </div>
</template>

<style scoped>
    .social{
        display: flex;
        background-color: #181818;
        padding: 23px 20px;
        gap: 10px;
        align-items: center;
    }
    .social p{
        
        color: #FFF;
        text-align: center;
        font-family: "Inter";
        font-size: 20.445px;
        font-style: normal;
        font-weight: 400;
        line-height: normal;
    }
</style>
