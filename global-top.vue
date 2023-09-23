<!-- global-bottom.vue -->
<template>
    <img src="/images/bar-01.png" class="absolute top-0 left-0" />
    <div class="absolute top-5 left-5 w-15 flex gap-2 w-30 whitespace-nowrap align-center items-center">
        <img src="/images/logo.svg" class="w-10 " v-bind:data-index="$slidev.nav.currentPage" />
        React Live 2023
    </div>
    <div class="absolute bottom-2 left-10 ">
        <SlideCurrentNo class="text-xs" />
        <span class="text-xs pl-10">New Suspense Architecture in React 18</span>
    </div>
</template>