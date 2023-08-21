<script setup>
defineProps(["imageUrl"])
</script>

<template>
    <div class="start-up">
        <img :src="imageUrl" />
    </div>
    
</template>

<style scoped>
 .start-up{
    border-radius: 8px;
    background: #F5F5F5;
    
 }
</style>