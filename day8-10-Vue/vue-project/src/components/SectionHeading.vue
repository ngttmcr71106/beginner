<script setup>
defineProps({
    main: {
        type: String,
        required: true
    },
    sub: {
        type: String,
        required: true
    }
})
</script>

<template>
    <h2 class="text-center mb-10">
        <span class="text-[40px] md:text-[64px] block">{{ main }}</span>
        <span class="text-[12px] md:text-lg block">{{ sub }}</span>
    </h2>
</template>