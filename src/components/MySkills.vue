<template>
    <div id="skillsId" class="pt-50 flex items-center justify-center pb-30">
        <h1 class="cool-font text-4xl font-extrabold text-center">MySkills</h1>
    </div>
    <div class="flex flex-row justify-center pb-100">

        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Frontend</h4>
            <div class="pt-10 grid grid-cols-5 pr-20 pl-23 gap-y-4">
                <MyIcon :newIcon="'skill-icons:html'" />
                <MyIcon :newIcon="'skill-icons:css'" />
                <MyIcon :newIcon="'skill-icons:javascript'" />
                <MyIcon :newIcon="'skill-icons:typescript'" />
                <MyIcon :newIcon="'skill-icons:vuejs-dark'" />
                <MyIcon :newIcon="'skill-icons:pinia-dark'" />
                <MyIcon :newIcon="'skill-icons:bootstrap'" />
                <MyIcon :newIcon="'skill-icons:vite-dark'" />
                <MyIcon :newIcon="'skill-icons:tailwindcss-dark'" />
                <MyIcon :newIcon="'skill-icons:nuxtjs-dark'" />
                

            </div>
        </div>
        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Backend/Server</h4>
            <div class="pt-10 grid grid-cols-5 gap-y-4 pr-20 pl-23">
                <MyIcon :newIcon="'skill-icons:nodejs-dark'" />
                <MyIcon :newIcon="'skill-icons:expressjs-dark'" />
                <MyIcon :newIcon="'skill-icons:c'" />
                <MyIcon :newIcon="'skill-icons:cpp'" />
                <MyIcon :newIcon="'skill-icons:java-dark'" />
                <MyIcon :newIcon="'skill-icons:mongodb'" />
                <MyIcon :newIcon="'skill-icons:python-dark'" />
                <MyIcon :newIcon="'skill-icons:php-dark'" />
                <MyIcon :newIcon="'skill-icons:cloudflare-dark'" />
                <MyIcon :newIcon="'skill-icons:netlify-dark'" />
            </div>
        </div>
        <div class="basis-1/3 text-center">
            <h4 class="cool-font text-xl font-bold">Tools</h4>
            <div class="pt-10 grid grid-cols-5 gap-y-4 pr-20 pl-23">
                <MyIcon :newIcon="'skill-icons:arduino'" />
                <MyIcon :newIcon="'skill-icons:bash-dark'" />
                <MyIcon :newIcon="'skill-icons:npm-dark'" />
                <MyIcon :newIcon="'skill-icons:pnpm-dark'" />
                <MyIcon :newIcon="'skill-icons:powershell-dark'" />
                <MyIcon :newIcon="'#'" />
                <MyIcon :newIcon="'skill-icons:github-dark'" />
                <MyIcon :newIcon="'skill-icons:windows-dark'" />
                <MyIcon :newIcon="'skill-icons:git'" />
                
            </div>
        </div>

    </div>

</template>

<script setup lang="ts">
import MyIcon from './MyIcon.vue'
</script>