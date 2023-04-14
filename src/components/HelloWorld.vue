<script setup>
import { ref } from 'vue'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faLinkedin, faGithub, faInstagram } from '@fortawesome/free-brands-svg-icons'
</script>

<template>



<nav class="flex items-center justify-between flex-wrap bg-cyan-700 py-6 px-80 mb-16">
    <!-- <div class="flex items-center flex-shrink-0 text-white mr-6">
        <svg class="fill-current h-8 w-8 mr-2" width="54" height="54" viewBox="0 0 54 54" xmlns="http://www.w3.org/2000/svg"><path d="M13.5 22.1c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05zM0 38.3c1.8-7.2 6.3-10.8 13.5-10.8 10.8 0 12.15 8.1 17.55 9.45 3.6.9 6.75-.45 9.45-4.05-1.8 7.2-6.3 10.8-13.5 10.8-10.8 0-12.15-8.1-17.55-9.45-3.6-.9-6.75.45-9.45 4.05z"/></svg>
        <span class="font-semibold text-xl tracking-tight">Robinson</span>
    </div> -->
    <!-- <div class="block lg:hidden">
        <button class="flex items-center px-3 py-2 border rounded text-teal-200 border-teal-400 hover:text-white hover:border-white">
        <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
        </button>
    </div> -->
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
            <a href="#" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
                Sobre
            </a>
            <a href="#" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
                Posts
            </a>
        </div>
        <div>
            <a href="https://github.com/robinson4k" class="inline-block text-sm px-4 py-2 leading-none border rounded text-white border-white hover:border-transparent hover:text-teal-500 hover:bg-white mt-4 lg:mt-0"><font-awesome-icon class="text-base" :icon="faGithub" /> GitHub</a>
        </div>
    </div>
</nav>

<div class="text-center text-[#F8F8F2]">
    <img src="/images/eu-robinson.png" alt="Robinson Silva avatar" class="mx-auto rounded-md mb-6" width="160px" height="160px">
    <h1 class="text-6xl mb-4">Robinson Silva</h1>

    <h2 class="text-xl mb-2">Analista de sistemas, desenvolvedor, líder de equipe e apaixonado por resolver problemas</h2>

    <p class="mb-16"><a href="mailto:robinson4k@gmail.com">robinson4k@gmail.com</a></p>

    <div class="max-w-[48ch] mx-auto flex justify-between text-lg">
        <div>
            <a href="https://www.linkedin.com/in/robinson4k" target="_blank" rel="LinkedIn Robinson">
                <font-awesome-icon class="text-3xl" :icon="faLinkedin" /> /in/robinson4k
            </a>
        </div>
        <div>
            <a href="https://github.com/robinson4k" target="_blank" rel="GitHub Robinson">
                <font-awesome-icon class="text-3xl" :icon="faGithub" /> /robinson4k
            </a>
        </div>
        <div>
            <a href="https://www.instagram.com/_robinsonsilva" target="_blank" rel="GitHub Robinson">
                <font-awesome-icon class="text-3xl" :icon="faInstagram" /> _robinsonsilva
            </a>
        </div>
    </div>
</div>

</template>

<style scoped>
svg.linkedin-icon {
    width: 24px;
    height: 24px;
    color: white;
}
</style>