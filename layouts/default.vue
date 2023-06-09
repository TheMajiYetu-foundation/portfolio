<template>
    <div class="h-screen w-screen bg-blue-200 image">
        <NavBar/>

        <slot/>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>
.image{
    background-image: url('');
}
</style>