<template>
    <div @click="btn">
        子组件:{{obj}}
    </div>
</template>

<script>
    export default {
        props: ['obj'],
        methods: {
            btn() {
                this.obj = 33
            }
        },
    }
</script>
