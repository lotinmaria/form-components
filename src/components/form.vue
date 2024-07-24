<script setup>
import Input from './input.vue'

function save() {
    
}
</script>

<template>
    <form :action="save">
        <Input type="text" required="required" maxlength="55"/>
    </form>
</template>

<style scoped>
</style>