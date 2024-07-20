<script>
export default {
    name: 'Title',
    props: {
        type: {
            type: String,
            required: true
        },
    }
}
</script>

<template>
    <div>
        <slot></slot>
    </div>
</template>