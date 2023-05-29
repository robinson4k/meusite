<script setup>
import { ref } from 'vue'
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faLinkedin, faGithub, faInstagram } from '@fortawesome/free-brands-svg-icons'
</script>

<template>



<!-- <nav class="flex items-center justify-between flex-wrap bg-cyan-700 py-4 px-80 mb-16">
    <div class="w-full block flex-grow lg:flex lg:items-center lg:w-auto">
        <div class="text-sm lg:flex-grow">
            <a href="#" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
                Sobre
            </a>
            <a href="#" class="block mt-4 lg:inline-block lg:mt-0 text-teal-200 hover:text-white mr-4">
                Posts
            </a>
        </div>
    </div>
</nav> -->

<div class="text-center text-[#F8F8F2] mt-20">
    <img src="/images/eu-robinson.png" alt="Robinson Silva avatar" class="mx-auto rounded-md mb-6" width="160px" height="160px">
    <h1 class="text-6xl mb-4">Robinson Silva</h1>

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