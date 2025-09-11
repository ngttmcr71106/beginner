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
        <span class="text-4xl block">{{ main }}</span>
        <span class="text-sm block">{{ sub }}</span>
    </h2>
</template>