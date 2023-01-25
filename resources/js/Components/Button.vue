<script setup>
defineProps({
    type: {
        type: String,
        default: "submit",
    },
});
</script>

<template>
    <button
        :type="type"
        class="inline-flex items-center mt-6 px-5 py-3 bg-emerald-400 border border-transparent rounded-md font-bold text-xs text-white uppercase tracking-widest hover:bg-emerald-500 active:bg-emerald-500 focus:outline-none focus:bg-emerald-500 focus:shadow-outline-emerald transition ease-in-out duration-200"
    >
        <slot />
    </button>
</template>
