<template>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#111827" fill-opacity="1" d="M0,256L40,218.7C80,181,160,107,240,80C320,53,400,75,480,106.7C560,139,640,181,720,208C800,235,880,245,960,218.7C1040,192,1120,128,1200,106.7C1280,85,1360,107,1400,117.3L1440,128L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path></svg>
    <div class=" bg-gray-900 mb-50 pb-10">
        <div>
            <div class="flex flex-col items-center mb-20" id="my-services">
                <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Services</h4>
            </div>
        </div>
        <div class="grid lg:grid-cols-4 grid-cols-2 gap-8 p-2 text-white">
            <div class=" flex flex-col items-center text-center border rounded-xl p-5">
                <Icon class="w-10 h-10" icon="devicon-plain:html5"></Icon>
                <h3 class="font-bold text-xl">Frontend Developer</h3>
                <p>I work in frontend development, transforming designs and ideas into modern, fast, and intuitive
                    interfaces.</p>
            </div>
            <div class=" flex flex-col items-center text-center border rounded-xl p-5">
                <Icon class="w-10 h-10" icon="tdesign:system-code"></Icon>
                <h3>Back-end developer</h3>
                <p>I specialize in backend development, designing and implementing robust, scalable and secure
                    architectures.</p>
            </div>
            <div class=" flex flex-col items-center text-center border rounded-xl p-5">
                <Icon class="w-10 h-10" icon="material-symbols:stylus-note-rounded"></Icon>
                <h3>Web Designer</h3>
                <p>I work as a web designer, creating modern, intuitive, and responsive interfaces that combine
                    aesthetics and functionality.</p>
            </div>
            <div class=" flex flex-col items-center text-center border rounded-xl p-5">
                <Icon class="w-10 h-10" icon="tdesign:system-setting-filled"></Icon>
                <h3>System builder</h3>
                <p>I specialize in computer assembly and configuration, selecting and assembling hardware components to
                    create high-performance, stable, and custom systems.</p>
            </div>
        </div>
    </div>

</template>

<script setup>
import { Icon } from '@iconify/vue';
</script>