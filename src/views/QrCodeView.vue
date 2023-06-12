<script setup lang="ts">
import QrCodeCard from '@/components/QrCodeCard.vue';
</script>

<template>
    <div class="qr-code-view">
        <QrCodeCard />
    </div>
</template>

<style>
    .qr-code-view{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        
        height: 100vh;
    }
</style>