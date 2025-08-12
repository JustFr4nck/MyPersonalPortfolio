<template>
    <div>
        <nav class="h-25 navStyle">
            <div class="flex justify-start p-5">
                <div class="absolute inset-y-0 pt-7 pl-30 linkSpace">
                    <h2 class="titleDiv">JustFranck</h2>
                </div>
                
                <div class="absolute inset-y-0 right-0 pt-9 pr-100 linkSpace">

                    <a class="text-lg m-6 group relative w-max">
                        <span>
                            Home
                        </span>
                        <span
                            class="absolute -bottom-1 left-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                        <span
                            class="absolute -bottom-1 right-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                    </a>

                    <a @click="scrollToAbout" class="text-lg m-6 group relative w-max">
                        <span>
                            About
                        </span>
                        <span
                            class="absolute -bottom-1 left-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                        <span
                            class="absolute -bottom-1 right-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                    </a>

                    <a @click="scrollToServices"  class="text-lg m-6 group relative w-max">
                        <span>
                            Services
                        </span>
                        <span
                            class="absolute -bottom-1 left-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                        <span
                            class="absolute -bottom-1 right-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                    </a>

                    <a class="text-lg m-6 group relative w-max">
                        <span>
                            Skills
                        </span>
                        <span
                            class="absolute -bottom-1 left-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                        <span
                            class="absolute -bottom-1 right-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                    </a>
                    
                    <a class="text-lg m-6 group relative w-max">
                        <span>
                            Contact
                        </span>
                        <span
                            class="absolute -bottom-1 left-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                        <span
                            class="absolute -bottom-1 right-1/2 w-0 transition-all h-0.5 bg-indigo-600 group-hover:w-3/6"></span>
                    </a>

                    <div class="vertical-divider"></div>
                    <div class="ml-150 -mt-15">
                        <button @click="visitCv" class="btnCv" >Download CV 📄</button>
                    </div>
                </div>
            </div>
        </nav>
    </div>


</template>

<script setup>

            //cv button  
       
            function visitCv(){

                window.open("https://europa.eu/europass/eportfolio/api/eprofile/shared-profile/francesco-perrotta/3bc81d7c-3ed2-4015-aa6f-07ea6c0f8319?view=html","_blank");

            }

            //scroll to about
            function scrollToAbout(){
                const aboutId = document.getElementById("aboutId");
                aboutId.scrollIntoView({behavior: 'smooth'});
            }
            
            //scroll to services
            function scrollToServices(){
                const servicesId = document.getElementById("servicesId");
                servicesId.scrollIntoView({behavior: 'smooth'});
            }
            
            
   
</script>