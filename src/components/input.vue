<script setup>

const info = defineProps({
    type: {
        type: String,
        default: "text",
    },
    default: {
        type: null,
        default: ""
    },
    required: {
        type: String,
        default: "",
    },
    min_length: {
        type: Number,
    },
    min: {
        type: Number,
    },
    maxlength: {
        type: Number,
    }

})
</script>

<template>
    <input :type="info.type" :default="info.default" info.required :min_length="info.min_length" :min="info.min">
</template>

<style></style>