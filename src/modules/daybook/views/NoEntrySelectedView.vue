<template>
    <div class="d-flex justify-content-center">
        <h1 class="align-self-center">No entry Selected</h1>
    </div>
    <FActionButton />
</template>

<script>

    import { defineAsyncComponent } from 'vue'

    export default {
        name: "NoEntrySelectedView",

        components: {

            FActionButton: defineAsyncComponent(() => import('../components/FActionButton.vue'))

        }

    }
</script>

<style lang="scss" scoped>

    div {
        height: 100vh;
    }

</style>