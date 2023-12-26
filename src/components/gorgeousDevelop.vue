<template>
    <div>
        <p>{{ name }}</p><br>
        <button @click="updateName">Change name</button>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: 'Gorgeous Develop',
        }
    },

    methods: {
        updateName() {
            this.name = 'Gorgeous Develop Team';
        }
    }
}

</script>

<style scoped>

</style>