<template lang="jade">
  div
    p {{ greeting }} World!
</template>

<script>
export default {
    components: {

    },
    data () {
        return {
            greeting: 'Hello'
        }
    }
}
</script>

<style lang="stylus" scoped>
p
    font-size 2em
    text-align center
</style>