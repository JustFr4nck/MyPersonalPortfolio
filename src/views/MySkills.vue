<template>
    <div class="flex flex-col items-center mb-100" id="my-skills">
        <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Skills</h4>
        <div class="flex lg:flex-row md:flex-col flex-col lg:gap-20 gap-5 items-center">
            <div class="flex flex-col">
                <div class="text-white text-center pt-10">
                    <h4 class="font-bold text-2xl ">Frontend</h4>
                </div>
                <div class="pt-10 grid lg:grid-cols-5 grid-cols-3 gap-8 justify-items-center">
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowOrange ">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-html"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">HTML</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue ">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-css2"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">CSS</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowYellow ">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-js-official"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">JavaScript</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue ">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-typescript-official"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">TypeScript</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGreen ">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-vue"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Vue</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowPurple">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-vite"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Vite</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowPurple">
                        <Icon class="w-15 h-15" icon="devicon:bootstrap"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Bootstrap</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-tailwind"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Tailwind</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGreen">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-nuxt"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Nuxt</h6>
                    </div>
                    <div
                        class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowYellow col-span-3  sm:col-span-1">
                        <Icon class="w-15 h-15" icon="logos:pinia"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Pinia</h6>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="text-white text-center pt-10">
                    <h4 class="font-bold text-2xl">Backend</h4>
                </div>
                <div class="pt-10 grid lg:grid-cols-5 grid-cols-3 gap-8 justify-items-center">
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGreen">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-node"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Node.js</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGray">
                        <Icon class="w-15 h-15" icon="devicon:express"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Express</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-c2"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">C</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-cpp3"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">C++</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowOrange">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-java"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Java</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGreen">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-mongo"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">MongoDB</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowOrange">
                        <Icon class="w-15 h-15" icon="devicon:mysql-wordmark"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">MySQL</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowYellow">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-python"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Python</h6>
                    </div>
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowPurple">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-php2"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">PHP</h6>
                    </div>
                    <div
                        class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl col-span-3 md:col-span-1 sm:col-span-1 iconShadowBlue">
                        <Icon class="w-15 h-15" icon=vscode-icons:file-type-go></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Go</h6>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex flex-col">
            <div class="text-white text-center pt-15">
                <h4 class="font-bold text-2xl">Tools</h4>
            </div>
            <div class="pt-10 grid lg:grid-cols-5 grid-cols-3 gap-8 justify-items-center">
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                    <Icon class="w-15 h-15" icon="vscode-icons:file-type-arduino"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Arduino</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGray">
                    <Icon class="w-15 h-15" icon="devicon:bash"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Bash</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowRed">
                    <Icon class="w-15 h-15" icon="devicon:npm-wordmark"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">npm</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowOrange">
                    <Icon class="w-15 h-15" icon="vscode-icons:file-type-light-pnpm"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">pnpm</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                    <Icon class="w-15 h-15" icon="vscode-icons:file-type-powershell"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Powershell</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGray">
                    <Icon class="w-15 h-15" icon="skill-icons:github-light"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Github</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowRed">
                    <Icon class="w-15 h-15" icon="devicon:git"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Git</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowBlue">
                    <Icon class="w-15 h-15" icon="vscode-icons:file-type-light-netlify"></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Netlify</h6>
                </div>
                <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowOrange">
                    <Icon class="w-15 h-15" icon=devicon:cloudflare></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">Cloudflare</h6>
                </div>
                <div
                    class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl col-span-3 md:col-span-1 sm:col-span-1 iconShadowBlue">
                    <Icon class="w-15 h-15" icon=devicon:sourcetree></Icon>
                    <h6 class="text-center rubik-bubbles-regular text-white font-bold">SourceTree</h6>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>