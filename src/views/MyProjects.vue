<template>
    <div class="bg-gray-900 flex flex-col pb-30 items-center">
        <div>
            <div class="flex flex-col items-center mb-20 pt-5" id="my-services">
                <h4 class="text-orange-600 font-bold rubik-bubbles-regular text-3xl">My Projects</h4>
            </div>
        </div>
        <div class="carousel w-130 lg:w-200 rounded-xl">
            <div id="slide1" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-170 rounded-xl" src="../assets/images/commitSite.png" alt="">
                <h1 class="text-white font-bold text-xl">Commit booking</h1>
                <h4 class="text-white">A meeting room booking site for the company commit software</h4>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide3" class="btn btn-circle">❮</a>
                    <a href="#slide2" class="btn btn-circle">❯</a>
                </div>
            </div>
            <div id="slide2" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-170 rounded-xl" src="../assets/images/dragonTris.png" alt="">
                <h1 class="text-white font-bold text-xl">Dragon tris</h1>
                <h4 class="text-white">A meeting room booking site for the company commit software</h4>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide1" class="btn btn-circle">❮</a>
                    <a href="#slide3" class="btn btn-circle">❯</a>
                </div>
            </div>
            <div id="slide3" class="carousel-item relative w-full flex flex-col items-center">
                <img class="w-100 lg:w-170 rounded-xl" src="../assets/images/piniaTasks.png" alt="">
                <h1 class="text-white font-bold text-xl">Pinia tasks</h1>
                <h4 class="text-white">A meeting room booking site for the company commit software</h4>
                <div class="absolute left-5 right-5 top-1/2 flex -translate-y-1/2 transform justify-between">
                    <a href="#slide2" class="btn btn-circle">❮</a>
                    <a href="#slide1" class="btn btn-circle">❯</a>
                </div>
            </div>
        </div>
    </div>
</template>