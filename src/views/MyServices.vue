<template>
    <div class="flex flex-col">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" class="waveFix">
            <path fill="#111827" fill-opacity="1"
                d="M0,64L26.7,53.3C53.3,43,107,21,160,32C213.3,43,267,85,320,133.3C373.3,181,427,235,480,224C533.3,213,587,139,640,96C693.3,53,747,43,800,53.3C853.3,64,907,96,960,138.7C1013.3,181,1067,235,1120,250.7C1173.3,267,1227,245,1280,208C1333.3,171,1387,117,1413,90.7L1440,64L1440,320L1413.3,320C1386.7,320,1333,320,1280,320C1226.7,320,1173,320,1120,320C1066.7,320,1013,320,960,320C906.7,320,853,320,800,320C746.7,320,693,320,640,320C586.7,320,533,320,480,320C426.7,320,373,320,320,320C266.7,320,213,320,160,320C106.7,320,53,320,27,320L0,320Z">
            </path>
        </svg>
        <div class="bg-gray-900 pb-35">
            <div>
                <div class="flex flex-col items-center mb-20 pt-5" id="my-services">
                    <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Services</h4>
                </div>
            </div>
            <div class="grid lg:grid-cols-4 grid-cols-2 gap-8 p-2 text-white ">
                <div class=" flex flex-col items-center text-center rounded-xl p-5 transform transition-transform duration-300 hover:-translate-y-3 divServOver hover:-rotate-4">
                    <Icon class="w-10 h-10 mb-3" icon="devicon-plain:html5"></Icon>
                    <h3 class="font-bold text-xl rubik-bubbles-regular mainText">Frontend Developer</h3>
                    <p>I work in frontend development, transforming designs and ideas into modern, fast, and intuitive
                        interfaces.</p>
                </div>
                <div class=" flex flex-col items-center text-center rounded-xl p-5 transform transition-transform duration-300 divServOver
            hover:-translate-y-3 hover:rotate-4 ">
                    <Icon class="w-10 h-10 mb-3" icon="tdesign:system-code"></Icon>
                    <h3 class="rubik-bubbles-regular font-bold text-xl mainText">Back-end developer</h3>
                    <p>I specialize in backend development, designing and implementing robust, scalable and secure
                        architectures.</p>
                </div>
                <div class=" flex flex-col items-center text-center rounded-xl p-5 transform transition-transform duration-300 divServOver
            hover:-translate-y-3 hover:-rotate-4">
                    <Icon class="w-10 h-10 mb-3" icon="material-symbols:stylus-note-rounded"></Icon>
                    <h3 class="rubik-bubbles-regular font-bold text-xl mainText">Web Designer</h3>
                    <p>I work as a web designer, creating modern, intuitive, and responsive interfaces that combine
                        aesthetics and functionality.</p>
                </div>
                <div class=" flex flex-col items-center text-center rounded-xl p-5 transform transition-transform duration-300 divServOver
            hover:-translate-y-3 hover:rotate-4">
                    <Icon class="w-10 h-10 mb-3" icon="tdesign:system-setting-filled"></Icon>
                    <h3 class="rubik-bubbles-regular font-bold text-xl mainText">System builder</h3>
                    <p>I specialize in computer assembly and configuration, selecting and assembling hardware components
                        to
                        create high-performance, stable, and custom systems.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>