<template>
    <div class="bg-gray-900 flex flex-col pb-12 items-center pt-12 min-h-screen justify-center overflow-hidden px-4">
        <div class="flex flex-col items-center mb-8" id="my-projects">
            <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl lg:text-4xl tracking-wider uppercase drop-shadow-[0_5px_5px_rgba(234,88,12,0.2)]">My Projects</h4>
        </div>

        <div class="w-full max-w-4xl rounded-2xl shadow-[0_20px_50px_rgba(0,0,0,0.5)] bg-gray-950/40 backdrop-blur-sm border border-gray-800/50 p-4 lg:p-6 overflow-hidden">

            <div class="carousel flex w-full overflow-x-auto scroll-smooth snap-x snap-mandatory gap-0">

                <div id="slide1" class="carousel-item relative w-full min-w-full flex flex-col items-center group transition-all duration-500 snap-start shrink-0">
                    <div class="w-full max-w-2xl aspect-video rounded-xl overflow-hidden border border-gray-800 shadow-lg">
                        <img class="w-full h-full object-cover transform group-hover:scale-[1.02] transition-transform duration-500" src="../assets/images/commitSite.png" alt="">
                    </div>
                    <h1 class="text-white font-extrabold text-xl lg:text-2xl mt-4 tracking-tight bg-gradient-to-r from-white to-gray-400 bg-clip-text text-transparent">Commit booking</h1>
                    <h4 class="text-gray-400 text-center max-w-xl mt-1 text-xs lg:text-sm font-medium px-4">A meeting room booking site for the company commit software</h4>

                    <div class="grid grid-cols-4 lg:grid-cols-8 gap-3 mt-4 text-xs lg:text-sm bg-gray-900/50 p-3 rounded-xl border border-gray-800/40 shadow-inner max-w-2xl w-full mx-auto">
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:nuxtjs-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Nuxt</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:vuejs-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Vue</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:typescript"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">TypeScript</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:tailwindcss-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Tailwind</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:supabase-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Supabase</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:vite-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Vite</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:javascript"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">JS</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:css"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Css</p>
                        </div>
                    </div>

                    <div class="mt-4">
                        <button @click="visitGitHub(commitGit)" class="text-gray-900 rounded-lg gitHubButton flex flex-row justify-center items-center gap-2 text-xs lg:text-sm">Link for Github <Icon class="text-base" icon="catppuccin:folder-github"></Icon></button>
                    </div>

                    <div class="absolute left-0 right-0 top-1/3 flex transform justify-between pointer-events-none px-2 lg:px-4">
                        <a href="#slide3" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❮</a>
                        <a href="#slide2" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❯</a>
                    </div>
                </div>

                <div id="slide2" class="carousel-item relative w-full min-w-full flex flex-col items-center group transition-all duration-500 snap-start shrink-0">
                    <div class="w-full max-w-2xl aspect-video rounded-xl overflow-hidden border border-gray-800 shadow-lg">
                        <img class="w-full h-full object-cover transform group-hover:scale-[1.02] transition-transform duration-500" src="../assets/images/foxybank.png" alt="">
                    </div>
                    <h1 class="text-white font-extrabold text-xl lg:text-2xl mt-4 tracking-tight bg-gradient-to-r from-white to-gray-400 bg-clip-text text-transparent">Foxy Bank</h1>
                    <h4 class="text-gray-400 text-center max-w-xl mt-1 text-xs lg:text-sm font-medium px-4">Banking application with OAuth 2.0 authentication</h4>

                    <div class="grid grid-cols-4 lg:grid-cols-7 gap-3 mt-4 text-xs lg:text-sm bg-gray-900/50 p-3 rounded-xl border border-gray-800/40 shadow-inner max-w-2xl w-full mx-auto">
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:angular-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Angular</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:typescript"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">TypeScript</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:html"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Html</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:css"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Css</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:tailwindcss-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Tailwind</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:php-dark"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">PHP/Slim</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:mysql-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">MySql</p>
                        </div>
                    </div>

                    <div class="mt-4">
                        <button @click="visitGitHub(dragonGit)" class="text-gray-900 rounded-lg gitHubButton flex flex-row justify-center items-center gap-2 text-xs lg:text-sm">Link for Github <Icon class="text-base" icon="catppuccin:folder-github"></Icon></button>
                    </div>

                    <div class="absolute left-0 right-0 top-1/3 flex transform justify-between pointer-events-none px-2 lg:px-4">
                        <a href="#slide1" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❮</a>
                        <a href="#slide3" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❯</a>
                    </div>
                </div>

                <div id="slide3" class="carousel-item relative w-full min-w-full flex flex-col items-center group transition-all duration-500 snap-start shrink-0">
                    <div class="w-full max-w-2xl aspect-video rounded-xl overflow-hidden border border-gray-800 shadow-lg">
                        <img class="w-full h-full object-cover transform group-hover:scale-[1.02] transition-transform duration-500" src="../assets/images/piniaTasks.png" alt="">
                    </div>
                    <h1 class="text-white font-extrabold text-xl lg:text-2xl mt-4 tracking-tight bg-gradient-to-r from-white to-gray-400 bg-clip-text text-transparent">Pinia tasks</h1>
                    <h4 class="text-gray-400 text-center max-w-xl mt-1 text-xs lg:text-sm font-medium px-4">A task manager built with Pinia's storage</h4>

                    <div class="grid grid-cols-4 lg:grid-cols-7 gap-3 mt-4 text-xs lg:text-sm bg-gray-900/50 p-3 rounded-xl border border-gray-800/40 shadow-inner max-w-2xl w-full mx-auto">
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:vuejs-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Vue</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:javascript"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">JS</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:html"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Html</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:css"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Css</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:tailwindcss-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Tailwind</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:vite-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Vite</p>
                        </div>
                        <div class="flex flex-col items-center">
                            <Icon class="w-7 h-7 iconHover rounded-lg transition-transform hover:scale-110 duration-300" icon="skill-icons:pinia-light"></Icon>
                            <p class="font-bold text-center text-gray-400 mt-1 text-[10px] lg:text-xs">Pinia</p>
                        </div>
                    </div>

                    <div class="mt-4">
                        <button @click="visitGitHub(piniaTasksGit)" class="text-gray-900 rounded-lg gitHubButton flex flex-row justify-center items-center gap-2 text-xs lg:text-sm">Link for Github <Icon class="text-base" icon="catppuccin:folder-github"></Icon></button>
                    </div>

                    <div class="absolute left-0 right-0 top-1/3 flex transform justify-between pointer-events-none px-2 lg:px-4">
                        <a href="#slide2" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❮</a>
                        <a href="#slide1" class="btn btn-sm lg:btn-md btn-circle bg-gray-900/80 border-gray-700 text-white hover:bg-orange-600 hover:border-orange-600 shadow-lg pointer-events-auto transition-all duration-300 backdrop-blur-sm">❯</a>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
import { Icon } from '@iconify/vue';
import { ref } from 'vue';

const commitGit = ref("https://github.com/JustFr4nck/SitoPrenotazioniCommit");
const dragonGit = ref("https://github.com/JustFr4nck/FoxyBank");
const piniaTasksGit = ref("https://github.com/JustFr4nck/PiniaTasks");

function visitGitHub(link: string) {
    window.open(link, "_blank");
}
</script>

<style scoped>
.gitHubButton {
    background: linear-gradient(135deg, #ffffff 0%, #f3f4f6 100%);
    padding: 8px 16px;
    font-weight: 600;
    letter-spacing: 0.025em;
    border: 1px solid rgba(255, 255, 255, 0.8);
    box-shadow: 0 4px 12px rgba(255, 255, 255, 0.1), 0 12px 24px rgba(0, 0, 0, 0.2);
    transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
}

.gitHubButton:hover {
    transform: translateY(-2px);
    background: linear-gradient(135deg, #ffffff 0%, #e5e7eb 100%);
    box-shadow: 0 0 20px rgba(255, 255, 255, 0.25), 0 15px 30px rgba(0, 0, 0, 0.3);
}

.gitHubButton:active {
    transform: translateY(1px);
    background-color: #030712;
    color: #ffffff;
    border-color: #1f2937;
}


.carousel::-webkit-scrollbar {
    display: none;
}
.carousel {
    -ms-overflow-style: none;
    scrollbar-width: none;
}
</style>
