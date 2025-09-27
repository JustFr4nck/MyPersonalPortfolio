<template>
    <div class="flex flex-col items-center">
        <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Skills</h4>
        <div class="flex lg:flex-row md:flex-col flex-col lg:gap-20 gap-5 items-center">
            <div class="flex flex-col">
                <div class="text-white text-center pt-10">
                    <h4 class="font-bold ">Frontend</h4>
                </div>
                <div class="pt-10 flex flex-row gap-8">
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

                </div>
                <div class="pt-10 flex flex-row basis-1/5 gap-8">
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
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowYellow">
                        <Icon class="w-15 h-15" icon="skill-icons:pinia-dark"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Pinia</h6>
                    </div>
                </div>
            </div>
            <div class="flex flex-col">
                <div class="text-white text-center pt-10">
                    <h4 class="font-bold ">Backend</h4>
                </div>
                <div class="pt-10 flex flex-row basis-1/5 gap-8">
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
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowGreen">
                        <Icon class="w-15 h-15" icon="vscode-icons:file-type-vue"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Vue</h6>
                    </div>

                </div>
                <div class="pt-10 flex flex-row basis-1/5 gap-8">
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
                    <div class="flex flex-col justify-center items-center w-25 h-25 rounded-2xl iconShadowYellow">
                        <Icon class="w-15 h-15" icon="skill-icons:pinia-dark"></Icon>
                        <h6 class="text-center rubik-bubbles-regular text-white font-bold">Pinia</h6>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>