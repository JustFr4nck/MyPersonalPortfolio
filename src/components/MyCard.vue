<template>
    <div class="card shadow-sm cardStyle h-100 text-center w-80">
        <div class="card-body flex items-center flex-col ">
            <div class="h-1/2">
                <img class="w-15 mt-15" :src="icon" alt="">
            </div>
            <div class="h-1/2">
                <h2 class="text-2xl font-semibold">{{ title }}</h2>
                <p class="mt-5">{{ description }}</p>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

defineProps({

    icon: String,
    title: String,
    description: String
})
</script>