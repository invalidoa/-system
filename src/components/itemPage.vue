<template>
    <div class="item">
        <slot name="main"></slot>
    </div>
</template>

<script setup>

</script>

<style lang="scss">
.item {
    height: 480px;
    border: 1px solid rgb(158, 156, 156);
    margin: 20px;
    background-color: rgba(207, 207, 198, 0.781);
}
</style>