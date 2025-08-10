<template>
   
    <div class="flex flex-row">
        <div class="homeDiv basis-1/2">
            <img src="../assets/images/me2.jpg" alt="">
        </div>
        <div class="mt-70 basis-1/2">
            <p class=" text-sm cool-font">Hello, I'm</p>
            <br>
            <p class="cool-font text-4xl font-extrabold">FRANCESCO PERROTTA</p>
            <br>
            <span class="cool-font text-xl">and I'm a &nbsp;</span>
            <span class="cool-font-reverse font-extrabold text-4xl"> {{ textShowed }}</span><span class=" text-4xl cursor cool-font">|</span>
            <br>
            <p class=" cool-font mt-5 text-sm">I'm a computer science student 
                who's only recently entered the world of programming,<br> 
                but I'm a quick learner 
                and I'm ready to improve and work toward my goals.</p>
            <div class="w-40 mt-10 forclick flex space-x-2">
                <a :href="gitlink" target="_blank"><img src="../assets/images/icons/github.png" alt=""></a>
                <a :href="youtubeLink" target="_blank"><img src="../assets/images/icons/youtube.png" alt=""></a>
                <a :href="linkedinlink" target="_blank"><img src="../assets/images/icons/linkedin.png" alt=""></a>
                <a :href="instalink" target="_blank"><img src="../assets/images/icons/instagram.png" alt=""></a>
            </div>
            <div class="contactButton">
                <a :href="mail" target="_blank">
                    <button class="">Contact me</button>
                </a>
                
            </div>
        </div>
        
    </div>

    
    
</template>


<script setup>

    //setup link :href

    const youtubeLink = 'https://www.youtube.com/@catastrofranck';
    const linkedinlink = 'https://www.linkedin.com/in/francesco-perrotta-228b28374/';
    const instalink = 'https://www.instagram.com/__the.real.franck__?igsh=Y2doeXBidGx2c3pm&utm_source=qr';
    const gitlink = 'https://github.com/JustFr4nck';
    const mail = 'mailto:perrotta.francesco.job@gmail.com';
    //setup script autowriting

    import {ref, onMounted} from 'vue';

    var messages = [

        "Fullstack developer",
        "Pianist",
        "Web developer",
        "I.C.T. Student"
    ];

    const textShowed = ref('');
    let currentIndex = 0;
    let charIndex = 0;
    let isDeleting = false;

    const type = () => {

        const current = messages[currentIndex];

        if(isDeleting){
            charIndex--;
            textShowed.value = current.substring(0, charIndex);   
        }
        else{
            charIndex++;
            textShowed.value = current.substring(0, charIndex);
        }

        let speed = isDeleting ? 50 : 100;

        if(!isDeleting && charIndex === current.length + 1){
            isDeleting = true;
            speed = 1000;
        }

        if(isDeleting && charIndex === 0){

            isDeleting = false;
            currentIndex = (currentIndex + 1) % messages.length;
            speed = 300;
        }

        setTimeout(type, speed);
    };

    onMounted(type);

</script>