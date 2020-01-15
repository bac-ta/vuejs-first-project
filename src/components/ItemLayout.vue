<template>
    <div class="row">
        <Item v-for="item in items" :key="item">{{item}}</Item>
    </div>
</template>

<script>
    import Item from "@/components/Item";

    export default {
        name: "ItemLayout",
        props: {
            items: Array
        },
        components: {
            Item
        }
    }
</script>

<style scoped>

</style>