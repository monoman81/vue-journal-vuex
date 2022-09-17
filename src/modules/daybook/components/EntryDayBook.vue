<template>

    <div class="mb-3 pointer p-2 entry-container" @click="$router.push({ name: 'entry', params: { id: 10 } })">
        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">17</span>&nbsp;
            <span class="mx-1 fs-5">September</span>&nbsp;
            <span class="mx-2 fw-light">2022, saturday</span>
        </div>
        <div class="entry-description">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aspernatur, error excepturi fuga fugit inventore
            iusto laudantium minima praesentium velit! Accusantium delectus doloribus ducimus eos in ipsum laudantium
            libero soluta ut?
        </div>
    </div>

</template>

<script>
    export default {
        name: "EntryDayBook"
    }
</script>

<style lang="scss" scoped>

    .entry-container {
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;

        &:hover {
            background-color: lighten(grey, 45);
        }

        .entry-description {
            font-size: 12px;
        }

    }


</style>