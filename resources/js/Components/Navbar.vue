<script setup>
import { Head, Link } from '@inertiajs/vue3';
</script>

<template>
    <nav class="px-10 mt-10 fixed w-screen z-10">
        <div class="bg-gray-800 rounded-full p-4 flex justify-between items-center">
            <div class="satisfy-regular text-white font-brush-script flex items-center">
                <span class="text-[#68e0cf] text-xl">Moh</span>
                <span class="ml-2 text-lg">Sa'id</span>
            </div>
            <div class="hidden md:flex space-x-4">
                <!-- <a href="#" class="text-gray-300 hover:text-white">HOME</a> -->
                <a href="#about" class="text-gray-300 hover:text-white">ABOUT</a>
                <a href="#resume" class="text-gray-300 hover:text-white">RESUME</a>
                <a href="#skill" class="text-gray-300 hover:text-white">PORTFOLIO</a>
                <a href="#contact" class="text-gray-300 hover:text-white">CONTACTS</a>
            </div>
            <a href="/documents/CV Said.pdf" download
                class="border border-teal-400 text-teal-400 px-6 py-2 rounded-full hover:bg-teal-400 hover:text-black transition-colors">
                DOWNLOAD CV
            </a>
        </div>
    </nav>
</template>
