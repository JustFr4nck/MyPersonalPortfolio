<template>
    <div class="">
        <Icon :icon="newIcon"/>
    </div>
</template>

<script setup lang="ts">

    import { Icon } from '@iconify/vue';
    
    defineProps<{ newIcon: string }>()
    
</script>