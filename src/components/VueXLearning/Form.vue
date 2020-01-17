<template>
    <div>
        <label for="flavor">Favorite ice cream flavor?</label>
        <input id="flavor" @input="changed"/>
    </div>
</template>

<script>
    export default {
        name: "Form",
        methods: {
            changed(event) {
                this.$store.commit('changeFlavor', event.target.value);
            }
        }
    }
</script>

<style scoped>

</style>