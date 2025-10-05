<template>
    <div class="bg-gray-900 flex flex-col pb-30 items-center pt-30">
        <div class="flex flex-col items-center mb-10 pt-5" id="my-projects">
            <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Projects</h4>
        </div>
        <div class="carousel w-130 lg:w-300 rounded-xl">
            <div id="slide1" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-270 rounded-xl" src="../assets/images/commitSite.png" alt="">
                <h1 class="text-white font-bold text-xl">Commit booking</h1>
                <h4 class="text-white">A meeting room booking site for the company commit software</h4>
                <div class=" grid grid-cols-6 gap-3 mt-3">
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:nuxtjs-light"></Icon>
                        <p class="font-bold text-center">Nuxt</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vuejs-light"></Icon>
                        <p class="font-bold text-center">Vue</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:typescript"></Icon>
                        <p class="font-bold text-center">TypeScript</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:tailwindcss-light"></Icon>
                        <p class="font-bold text-center">Tailwind</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:supabase-light"></Icon>
                        <p class="font-bold text-center">Supabase</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vite-light"></Icon>
                        <p class="font-bold text-center">Vite</p>
                    </div>
                    <div class="flex flex-col items-center col-start-3">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:javascript"></Icon>
                        <p class="font-bold text-center">JavaScript</p>
                    </div>
                    <div class="flex flex-col items-center col-start-4">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:css"></Icon>
                        <p class="font-bold text-center">Css</p>
                    </div>
                </div>
                <div class="mt-5 mb-5">
                    <button @click="visitGitHub(commitGit)" class=" text-gray-900 rounded-lg gitHubButton flex flex-row justify-center">Link for Github <Icon class=" mt-1 ml-2" icon="catppuccin:folder-github"></Icon></button>
                </div>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide3" class="btn btn-circle" @click.prevent>❮</a>
                    <a href="#slide2" class="btn btn-circle">❯</a>
                </div>
            </div>
            <div id="slide2" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-270 rounded-xl" src="../assets/images/dragonTris.png" alt="">
                <h1 class="text-white font-bold text-xl">Dragon tris</h1>
                <h4 class="text-white">DragonBall style tris tic-tac-toe</h4>
                <div class=" grid grid-cols-7 gap-3 mt-3">
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vuejs-light"></Icon>
                        <p class="font-bold text-center">Vue</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:javascript"></Icon>
                        <p class="font-bold text-center">JavaScript</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:html"></Icon>
                        <p class="font-bold text-center">Html</p>
                    </div>
                    <div class="flex flex-col items-center col-start-4">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:css"></Icon>
                        <p class="font-bold text-center">Css</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:tailwindcss-light"></Icon>
                        <p class="font-bold text-center">Tailwind</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vite-light"></Icon>
                        <p class="font-bold text-center">Vite</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:pinia-light"></Icon>
                        <p class="font-bold text-center">Pinia</p>
                    </div>
                </div>
                <div class="mt-5 mb-5">
                    <button @click="visitGitHub(dragonGit)" class=" text-gray-900 rounded-lg gitHubButton flex flex-row justify-center">Link for Github <Icon class=" mt-1 ml-2" icon="catppuccin:folder-github"></Icon></button>
                </div>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide1" class="btn btn-circle">❮</a>
                    <a href="#slide3" class="btn btn-circle">❯</a>
                </div>
            </div>
            <div id="slide3" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-270 rounded-xl" src="../assets/images/piniaTasks.png" alt="">
                <h1 class="text-white font-bold text-xl">Pinia tasks</h1>
                <h4 class="text-white">A task manager built with Pinia's storedge</h4>
                <div class=" grid grid-cols-7 gap-3 mt-3">
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vuejs-light"></Icon>
                        <p class="font-bold text-center">Vue</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:javascript"></Icon>
                        <p class="font-bold text-center">JavaScript</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:html"></Icon>
                        <p class="font-bold text-center">Html</p>
                    </div>
                    <div class="flex flex-col items-center col-start-4">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:css"></Icon>
                        <p class="font-bold text-center">Css</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:tailwindcss-light"></Icon>
                        <p class="font-bold text-center">Tailwind</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:vite-light"></Icon>
                        <p class="font-bold text-center">Vite</p>
                    </div>
                    <div class="flex flex-col items-center">
                        <Icon class="w-8 h-8 iconHover rounded-lg" icon="skill-icons:pinia-light"></Icon>
                        <p class="font-bold text-center">Pinia</p>
                    </div>
                </div>
                <div class="mt-5 mb-5">
                    <button @click="visitGitHub(piniaTasksGit)" class=" text-gray-900 rounded-lg gitHubButton flex flex-row justify-center">Link for Github <Icon class=" mt-1 ml-2" icon="catppuccin:folder-github"></Icon></button>
                </div>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide2" class="btn btn-circle">❮</a>
                    <a href="#slide1" class="btn btn-circle">❯</a>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';
import { ref } from 'vue';

const commitGit = ref("https://github.com/JustFr4nck/SitoPrenotazioniCommit");
const dragonGit = ref("https://github.com/JustFr4nck/DragonTris");
const piniaTasksGit = ref("https://github.com/JustFr4nck/PiniaTasks");

function visitGitHub(link) {

    window.open(link, "_blank");

}

</script>

<style scoped>

.gitHubButton{

    background-color: white;
    padding: 8px;
    font-weight: 500;
    box-shadow: 0 0 10px white, 0 0 15px white, 0 0 20px gray;
    transition: 0.5s ease;
}

.gitHubButton:hover{

    box-shadow: 0 0 15px white, 0 0 20px gray, 0 0 25px gray;
}

.gitHubButton:active{

    background-color: black;
    color: white;
}

</style>