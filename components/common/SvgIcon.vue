<template>
    <div class="svg-icon" :class="`svg-icon--${props.name}`">
        <Icon :name="props.name" mode="svg" :size="props.size" />
    </div>
</template>

<script setup lang="ts">
const props = withDefaults(
    defineProps<{
        name: string
        size?: string
    }>(),
    {
        size: '24px',
    }
)
</script>

<style lang="scss">
.svg-icon {
    display: inline-block;

    svg {
        display: block;
    }
}
</style>
