<template>
    <div>
       <div class="navbar bg-base-100/[.06]">
      <div class="flex-1">
        <div class="h-16 w-16 rounded-full mx-4">
            <img src="@/assets/images/logo.jpeg" alt="" class="h-full w-full rounded-full">
        </div>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          
          <li v-for="link in links" :key='link.path'>
            <NuxtLink :to="link.path">
                <p class="text-xl text-white font-semibold font-serif">{{ link.title }}</p>
            </NuxtLink>
          </li>
        </ul>
      </div>
    </div>
    </div>
</template>

<script setup lang="ts">
const links = [
    {
        title:"Home",
        path:'/'
    },
     {
        title: "About",
        path: ''
    },
     {
        title: "Project",
        path: ''
    },
    {
        title: "Donate",
        path: ''
    }
]

</script>

<style scoped>

</style>