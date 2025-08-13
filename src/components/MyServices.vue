<template>
    <div class="flex items-center justify-center pt-50 pb-30" id="servicesId">
        <h1 class="cool-font text-4xl font-extrabold text-center">My Services</h1>
    </div>
    <div class="flex flex-row pb-100 justify-center w-full gap-20">

        <div class="card shadow-sm cardStyle h-100 text-center w-80">
            <div class="card-body flex items-center flex-col ">
                <div class="h-1/2">
                    <img class="w-15 mt-15" src="../assets/images/icons/frontEndIcon.png" alt="">
                </div>
                <div class="h-1/2">
                    <h2 class="text-2xl font-semibold">Frontend Developer</h2>
                    <p class="mt-5">A card component has a figure, a body part, and inside body there are title
                        and actions parts</p>
                </div>
            </div>
        </div>


        <div class="card shadow-sm cardStyle h-100 text-center w-80">
            <div class="card-body flex items-center">
                <div class="h-1/2">
                    <img class="w-15 mt-15" src="../assets/images/icons/backEndIcon.png" alt="">
                </div>
                <div class="h-1/2">
                    <h2 class="text-2xl font-semibold">Back-end developer</h2>
                    <p class="mt-5">A card component has a figure, a body part, and inside body there are title
                        and actions parts</p>
                </div>

            </div>
        </div>


        <div class="card shadow-sm cardStyle h-100 text-center w-80">
            <div class="card-body flex items-center">
                <div class="h-1/2">
                    <img class="w-15 mt-15" src="../assets/images/icons/webDesignerIcon.png" alt="">
                </div>
                <div class="h-1/2">
                    <h2 class="text-2xl font-semibold">Web Designer</h2>
                    <p class="mt-5">A card component has a figure, a body part, and inside body there are title
                        and actions parts</p>
                </div>

            </div>
        </div>


        <div class="card shadow-sm cardStyle h-100 text-center w-80">
            <div class="card-body flex items-center">
                <div class="h-1/2">
                    <img class="w-15 mt-15" src="../assets/images/icons/systemBuilderIcon.png" alt="">
                </div>
                <div class="h-1/2">
                    <h2 class="text-2xl font-semibold">System builder</h2>
                    <p class="mt-5">A card component has a figure, a body part, and inside body there are title
                        and actions parts</p>
                </div>

            </div>
        </div>

    </div>


</template>

<script setup>
import MyCard from "../components/MyCard.vue";
</script>
