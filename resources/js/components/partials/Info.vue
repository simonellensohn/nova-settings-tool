<template>
    <div class="flex items-center">
        <p class="text-80 leading-tight">
            <slot></slot> <a class="no-underline dim text-primary" :href="url" target="_blank">{{ __(text) }}</a>
        </p>
    </div>
</template>

<script>
export default {
    props: {
        text: String,
        url: String
    },
}
</script>
