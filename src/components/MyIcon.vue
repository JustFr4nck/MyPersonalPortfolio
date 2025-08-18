<template>
        <Icon class="iconSize" :icon="newIcon"/>
        
</template>

<script setup lang="ts">

    import { Icon } from '@iconify/vue';
    
    defineProps<{ newIcon: string }>()
    
</script>