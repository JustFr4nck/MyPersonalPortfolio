<template>
  <div class="flex justify-center items-center min-h-screen">
    <div class="relative w-64 h-64 group">
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
    <div>
      <p>Hello, I'm</p>
      <br />
      <p>FRANCESCO PERROTTA</p>
      <br />
      <span>and I'm a &nbsp;</span>
      <span class="font-extrabold text-4xl"> {{ textShowed }}</span
      ><span>|</span>
      <br />
      <p>
        I'm a computer science student who's only recently entered the world of programming,<br />
        but I'm a quick learner and I'm ready to improve and work toward my goals.
      </p>
    </div>
  </div>
</template>

<script setup lang="ts">
const youtubeLink = 'https://www.youtube.com/@catastrofranck'
const linkedinlink = 'https://www.linkedin.com/in/francesco-perrotta-228b28374/'
const instalink = 'https://www.instagram.com/__the.real.franck__?igsh=Y2doeXBidGx2c3pm&utm_source=qr'
const gitlink = 'https://github.com/JustFr4nck'
const mail = 'mailto:perrotta.francesco.job@gmail.com'

import { ref, onMounted } from 'vue'

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
