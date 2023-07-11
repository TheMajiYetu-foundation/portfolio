<template>
    <div>
        <div class="card w-96 bg-base-100 shadow-xl">
            <div class="flex items-center justify-center">
                <figure class="px-10 pt-10 h-40 w-40 ">
                    <img src="@/assets/images/people/profile.png" alt="Shoes" class="rounded-xl h-full w-full" />
                  </figure>
            </div>
            <div class="card-body items-center text-center">
              <h2 class="card-title text-3xl">{{ name }}</h2>
              <p>{{description}}</p>
              
            </div>
          </div>
    </div>
</template>

<script setup lang="ts">
defineProps({
    name:{
        type:String,
        required:true
    },
    description:{
        type:String,
        required:true
    }
})

</script>

<style scoped>

</style>