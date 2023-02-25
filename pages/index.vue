<template>
     <aside aria-label="Related articles" class="py-8 lg:py-24 bg-gray-50 dark:bg-gray-800">
        <div class="px-4 mx-auto max-w-screen-xl">
            <h2 class="mb-8 text-2xl font-bold text-gray-900 dark:text-white">Laracast Post</h2>
            <div class="grid gap-12 sm:grid-cols-2 lg:grid-cols-4">
                <post-item v-for="i in 12" :key="i" />
            </div>
        </div>
    </aside>
</template>
