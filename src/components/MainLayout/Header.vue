<template>
    <header data-layername="navbar" class="flex flex-col text-xs tracking-tight text-black max-w-[697px]">
      <nav class="flex flex-wrap gap-5 justify-between ml-5 w-full max-w-[606px] max-md:max-w-full">
        <div class="flex gap-5">
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/24735e51dec2cf3a2e820fa5539395afc5ed5d3298e4d5a9acbcf783027602d4?placeholderIfAbsent=true&apiKey=b642bcfadf164c35aebff8fb97b04ffb" class="object-contain shrink-0 w-8 aspect-[1.1] rounded-[100000px]" alt="Company logo" />
          <ul class="flex gap-4 justify-center items-center my-auto">
            <li data-layername="logo" class="self-stretch my-auto text-xs font-bold">
              <a href="/" class="focus:outline-none focus:underline">Home</a>
            </li>
            <li data-layername="shop" class="self-stretch my-auto">
              <a href="/about" class="focus:outline-none focus:underline">About Us</a>
            </li>
            <li data-layername="shop" class="self-stretch my-auto">
              <a href="/menu" class="focus:outline-none focus:underline">Menu</a>
            </li>
          </ul>
        </div>
        <button data-layername="login" class="gap-3 my-auto whitespace-nowrap focus:outline-none focus:ring-2 focus:ring-black">
          Login
        </button>
      </nav>
      <div class="w-full border-black min-h-[1px] max-md:max-w-full" role="separator"></div>
    </header>
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  
  export default defineComponent({
    name: 'Navbar',
  });
  </script>