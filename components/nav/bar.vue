<template>
    <div>
       <div class="navbar bg-base-100/[.06]">
      <div class="flex-1">
        <div class="h-16 w-16 rounded-full mx-4">
            <img src="assets/images/logo.jpeg" alt="" class="h-full w-full rounded-full">
        </div>
      </div>
      <div class="flex-none">
        <ul class="menu menu-horizontal px-1">
          <li><a>Link</a></li>
          <li>
            <details>
              <summary>
                Parent
              </summary>
              <ul class="p-2 bg-base-100">
                <li><a>Link 1</a></li>
                <li><a>Link 2</a></li>
              </ul>
            </details>
          </li>
        </ul>
      </div>
    </div>
    </div>
</template>

<script setup lang="ts">


</script>

<style scoped>

</style>