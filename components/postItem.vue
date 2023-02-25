<template>
     <article class="max-w-xs">
        <nuxt-link to="/posts/1">
            <img src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/article/blog-1.png"
                class="mb-5 rounded-lg" alt="Image 1">
        </nuxt-link>
        <h2 class="mb-2 text-xl font-bold leading-tight text-gray-900 dark:text-white">
            <nuxt-link to="/posts/2">Our first office</nuxt-link>
        </h2>
        <p class="mb-4 font-light text-gray-500 dark:text-gray-400">Over the past year, Volosoft has undergone
            many changes! After months of preparation.</p>
        <nuxt-link to="/posts/1"
            class="inline-flex items-center font-medium underline underline-offset-4 text-primary-600 dark:text-primary-500 hover:no-underline">
            Read in 2 minutes
        </nuxt-link>
    </article>
</template>