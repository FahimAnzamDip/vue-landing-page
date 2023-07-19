<script setup>
const props = defineProps({
    btnType: String,
    link: String,
    class: {
        type: String,
        default: "text-sm sm:text-md md:text-base"
    }
});
</script>

<template>
    <a v-if="btnType === 'primary'" :href="link" v-smooth-scroll :class="class" class="font-theme-heading font-medium bg-theme-primary px-6 py-2 text-white rounded shadow-md hover:bg-white border-2 border-transparent hover:border-theme-primary hover:text-theme-primary cursor-pointer transition duration-200 mr-5">
        <slot></slot>
    </a>
    <a v-if="btnType === 'muted'" :href="link" v-smooth-scroll :class="class" class="font-theme-heading font-medium bg-gray-100 text-gray-500 px-6 py-2 rounded shadow-md hover:bg-white border-2 border-transparent hover:border-theme-grayish-blue hover:text-theme-grayish-blue cursor-pointer transition duration-200">
        <slot></slot>
    </a>
</template>
