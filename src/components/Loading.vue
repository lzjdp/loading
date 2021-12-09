<template>
    <div class="loading" v-if="show">加载中...</div>
</template>

<script>
export default {
    props: {
        show: {
            type: Boolean,
            default: true
        }
    }
}
</script>