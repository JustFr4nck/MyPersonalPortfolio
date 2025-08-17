<template>
    <div id="aboutId" class="flex pt-80">
        <div class="basis-1/2 ml-50 mb-100">
            <h1 class="titleAbout cool-font text-4xl font-extrabold pb-10">About me</h1>
            <p class="cool-font text-justify">
                My name is Francesco, and I was born on February 9, 2007, in Arezzo (Italy). <br>
                I'm studying computer science at the ITIS Meucci technical college in Florence. <br>
                Besides computer science, I love Japanese culture, which stems from my passion for anime and manga. <br>
                I play the piano, practice martial arts, and volunteer. <br>
                In the future I would like to become a professional software developer and I would like to delve into
                the world of cybersecurity.
            </p>
        </div>
        <div class="basis-1/2">
            <div class=" ml-50">

                <div class="group perspective w-100 h-100 ">

                    <div
                        class="relative w-full h-full transition-transform duration-700 transform-style-preserve-3d group-hover:rotate-y-180">

                        <div class="absolute w-full h-full backface-hidden rounded-full overflow-hidden imgAbout">
                            <img class="w-full h-full object-cover" src="../assets/images/MyIconTransparent.png" alt="">
                        </div>

                        <div class="absolute w-full h-full rotate-y-180 backface-hidden rounded-full overflow-hidden imgAbout">
                            <img class="w-full h-full object-cover" src="../assets/images/minime.jpeg" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

</template>
