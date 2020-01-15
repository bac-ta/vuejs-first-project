<template>
    <div class="col-sm-6 col-md-4 col-lg-3">
        <div class="card">
            <div class="card-body items">
                <slot></slot>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Item",
    }
</script>

<style scoped>
    .card-body {
        font-family: 'Symbola';
        font-size: 24px;
        color: black;
    }

    .items {
        cursor: pointer;
    }

    .items:hover {
        background-color: aliceblue;
    }
</style>