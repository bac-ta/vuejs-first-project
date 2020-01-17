<template>
    <div class="row">
        <form>
            <div>
                <label>U can saying...</label>
                <textarea class="form-group" v-model="item"></textarea>
            </div>
            <div>
                <button @click.prevent="createNew">Add</button>
            </div>
        </form>
    </div>
</template>

<script>
    export default {
        name: "NewItem",
        data() {
            return {
                item: ''
            }
        }
    }
</script>

<style scoped>

</style>