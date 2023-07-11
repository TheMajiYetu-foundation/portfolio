<template>
    <div class="h-fit w-screen bg-blue-200 image">
        <NavBar/>

        <slot/>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.image{
    background-image: url('assets/images/frame1.jpg');
}
</style>