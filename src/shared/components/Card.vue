<script>
import { ref } from 'vue'
export default {
    name: 'Card',
    setup() {
        return {
            // props
        }
    },
}
</script>

<template>
    <div class="container">
        <slot></slot>
    </div>
</template>

<style>
.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
}
</style>