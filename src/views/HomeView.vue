<template>
  <div class="flex flex-col justify-center items-center min-h-screen">
    <div class="mainText rubik-bubbles-regular text-4xl">
      <h2>Just_Franck</h2>
    </div>
    <div class="relative w-64 h-64 group mt-10">
      <div
        class="absolute inset-0 transition-transform duration-700 [transform-style:preserve-3d] group-hover:[transform:rotateY(180deg)]"
      >
        <div class="absolute inset-0 backface-hidden imgAbout">
          <img
            src="../assets/images/me.jpg"
            alt="me"
            class="w-full h-full object-cover rounded-full"
          />
        </div>

        <div
          class="absolute inset-0 backface-hidden [transform:rotateY(180deg)] imgAbout flex flex-col items-center justify-center p-4"
        >
          <div class="absolute inset-0 backface-hidden imgAbout">
            <img
              src="../assets/images/me2.jpg"
              alt="me"
              class="w-full h-full object-cover rounded-full"
            />
          </div>
        </div>
      </div>
    </div>
    <div class=" mt-10 text-center text-white font-bold">
      <p>Hello, I'm</p>
      <p>FRANCESCO PERROTTA</p>
      <span>and I'm a <br></span>
      <span class="font-extrabold text-4xl rubik-bubbles-regular"> {{ textShowed }}</span
      ><span class="text-4xl">|</span>
    </div>
    <div class="flex flex-row gap-2 mt-5">
      <a :href="youtubeLink" target="_blank"><icon class="w-8 h-8 text-white " icon="streamline-logos:youtube-clip-logo-block"></icon></a>
      <a :href="linkedinlink" target="_blank"><icon class="w-8 h-8 text-white" icon="streamline-logos:linkedin-logo-block"></icon></a>
      <a :href="instalink" target="_blank"><icon class="w-8 h-8 text-white" icon="streamline-logos:instagram-logo-2-block"></icon></a>
      <a :href="gitlink" target="_blank"><icon class="w-8 h-8 text-white" icon="streamline-logos:github-logo-2-block"></icon></a>
    </div>
    <div class="flex flex-row mt-8 gap-2 contactButton">
      <a :href="mail">Contact me 📩</a>
    </div>
    <span class=" arrow"></span>
  </div>
</template>

<script setup lang="ts">
const youtubeLink = 'https://www.youtube.com/@catastrofranck'
const linkedinlink = 'https://www.linkedin.com/in/francesco-perrotta-228b28374/'
const instalink = 'https://www.instagram.com/__the.real.franck__?igsh=Y2doeXBidGx2c3pm&utm_source=qr'
const gitlink = 'https://github.com/JustFr4nck'
const mail = 'mailto:perrotta.francesco.job@gmail.com'

import { ref, onMounted } from 'vue'
import { Icon } from '@iconify/vue';

const messages = ['Fullstack developer', 'Pianist', 'Web developer', 'I.C.T. Student']

const textShowed = ref('')
let currentIndex = 0
let charIndex = 0
let isDeleting = false

const type = () => {
  const current = messages[currentIndex]

  if (isDeleting) {
    charIndex--
    textShowed.value = current.substring(0, charIndex)
  } else {
    charIndex++
    textShowed.value = current.substring(0, charIndex)
  }

  let speed = isDeleting ? 50 : 100

  if (!isDeleting && charIndex === current.length + 1) {
    isDeleting = true
    speed = 1000
  }

  if (isDeleting && charIndex === 0) {
    isDeleting = false
    currentIndex = (currentIndex + 1) % messages.length
    speed = 300
  }

  setTimeout(type, speed)
}

onMounted(type)
</script>
