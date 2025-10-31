<template>
    <div class="border-b py-4">
        <button class="cursor-pointer flex justify-between w-full text-left font-bold text-lg focus:outline-none"
            @click="open = !open">
            <span>{{ title }}</span>
            <span class="text-gray-500">{{ open ? '−' : '+' }}</span>
        </button>

        <transition name="fade">
            <div v-if="open" class="mt-3 text-gray-700 text-sm leading-relaxed">
                <slot />
            </div>
        </transition>
    </div>
</template>

<script setup>
import { ref } from 'vue'
const props = defineProps({ title: String })
const open = ref(false)
</script>

<style scoped>
.fade-enter-active,
.fade-leave-active {
    transition: opacity 0.3s;
}

.fade-enter-from,
.fade-leave-to {
    opacity: 0;
}
</style>
