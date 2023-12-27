<template>
    <div>
        <h1>{{ title }}</h1>
        <p>{{ name }}</p><br>
        <button @click="updateName">Change name</button>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            required: true
        }
    },
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