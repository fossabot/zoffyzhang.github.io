<template lang="pug">
.page
    input(type="text", placeholder="test")
    input(type="text", placeholder="test")
    input(type="text", placeholder="test")
    button(@click="log") button
</template>

<script>
export default {
    data() {
        return {}
    },
    methods: {
        log() {
            console.log('ssdsdsds')
        }
    },
}
</script>

<style lang="scss">
.page {
    input {
        background: cyan;
    }
}
</style>
