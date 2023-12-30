<script setup>
defineProps({
    link: {
        type: String,
        required: true
    },
    logo: {
        type: String,
        required: true
    },
    color: {
        type: String,
        required: true
    },
    title: {
        type: String,
        required: true
    }
})
</script>

<template>
    <a :href="link" target="_blank">
        <div :class="['border-2', `border-${color}`, `bg-${color}`, 'bg-opacity-20', 'rounded-xl', 'w-[300px]', 'sm:w-[400px]', 'py-5', 'flex', 'items-center', 'hover:scale-105', 'transition-all', 'duration-200', 'ease', `hover:bg-${color}`, 'hover:bg-opacity-50', '!cursor-pointer', 'mt-3']">
            <div class="w-[50%] flex justify-center">
                <p class="text-gray-200 text-ml">{{ title }}</p>
            </div>
            <div class="w-[50%] flex justify-center">
                <img :src="logo" :alt="title" class="w-6 sm:w-10">
            </div>
        </div>
    </a>
</template>

<style scoped>

</style>