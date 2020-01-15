<template>
    <div id="app">
        <div class="container">
            <ItemLayout :items="items"/>
        </div>
    </div>
</template>

<script>

    import ItemLayout from "@/components/ItemLayout";

    export default {
        name: 'app',
        data() {
            return {
                items: ['Anh yeu em', 'Thi thoi em di voi vang, roi ngoai kia dong van nhe nhang'],
                maxItems: 10
            }
        },
        components: {
            ItemLayout
        }
    }
</script>

<style>

</style>
