<template>
    <section>
        <button @click="increment"></button>
    </section>
</template>

<script>
    export default {
        methods: {
            increment(){
                this.$store.dispatch('increment')
            }
        }

    }
</script>
<style>

</style>