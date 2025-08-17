<template>
    <div class="pt-50 flex items-center justify-center pb-30">
        <h1 class="cool-font text-4xl font-extrabold text-center">MySkills</h1>
    </div>
    <div class="flex flex-row justify-center">

        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Frontend</h4>
            <div>
                <MyIcon :newIcon="'logos:html-5'"/>
            </div>    
        </div>
        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Backend</h4>
        </div>
        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Tools</h4>
        </div>

    </div>
    
</template>

<script setup lang="ts">
    import MyIcon from './MyIcon.vue'
</script>