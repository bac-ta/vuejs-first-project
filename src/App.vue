<template>
    <div id="app">
        <!--        <div class="container">-->
        <!--            <ItemLayout :items="items"/>-->
        <!--        </div>-->
        <Form/>
        <Display/>
    </div>
</template>

<script>

    import Form from "@/components/VueXLearning/Form";
    import Display from "@/components/VueXLearning/Display";

    export default {
        name: 'app',
        data() {
            return {
                items: ['Anh yeu em', 'Thi thoi em di voi vang, roi ngoai kia dong van nhe nhang'],
                maxItems: 10
            }
        },
        components: {
            Display,
            Form
            // ItemLayout
        }
    }
</script>

<style>

</style>
