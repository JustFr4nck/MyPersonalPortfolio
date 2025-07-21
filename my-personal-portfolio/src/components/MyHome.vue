<template>

    <div class="flex flex-row">
        <div class="homeDiv basis-1/2">
            <img src="../assets/images/me2.jpg" alt="">
        </div>
        <div class="basis-1/2 mt-70">
            <p class=" text-sm cool-font">Hello, I'm</p>
            <br>
            <p class="cool-font text-4xl font-extrabold">FRANCESCO PERROTTA</p>
            <br>
            <span class="cool-font text-lg">and I'm a &nbsp;</span>
            <span class="cool-font font-extrabold text-4xl"> {{ textShowed }}</span><span class=" text-4xl cursor cool-font">|</span>
        
        </div>
    </div>
    
</template>


<script setup>

    import {ref, onMounted} from 'vue';

    var messages = [

        "Fullstak developer",
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