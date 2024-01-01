<template>
    <div>
        <p>header</p>
        <slot name="header" :gorgeous="gorgeous"></slot>
        <p>body</p>
        <slot></slot>
        <p>footer</p>
    </div>
</template>

<script>
export default {
    props: { 
        title: {
            type: String,
            required: false
        }
    },
    data() {
        return {
            gorgeous: 'develope',
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