<template>
    <div>
        <SectionsHero/>
        <div class="pt-10">
            <h3 class="text-4xl text-center text-white">Our Team</h3>
        </div>
        <div class="grid grid-cols-3 gap-x-20 gap-y-16 px-6 py-6">
            <div v-for="person in teams" :key="person.name">
                <UserCard :name="person.name" :description="person.description" />
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

definePageMeta({
    layout: "default",
    title: 'landing'

});

const teams = ref([
    {
        name:'Grace Muthoni',
        description:'Full stack developer, Cloud practitioner,Data analyst'
    },
    {
        name:'Mulati Brian',
        description:'Full stack developer, Cloud practitioner,Data analyst'
    },
    {
        name:'Grace Muthoni',
        description:'Full stack developer, Cloud practitioner,Data analyst'
    }
])
</script>

<style scoped></style>