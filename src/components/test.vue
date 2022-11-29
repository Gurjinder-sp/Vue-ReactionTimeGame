<template lang="">
    <div>
        {{name}}
        {{age}}
    </div>
</template>
<script>
export default {
    props: ['age'],
    data() {
        return {
            name : 'Player-1'
        }
    },
    methods: {
        onClick() {
            console.log("Button clicked")
        }
    },
    created() {
        
    }
}
</script>
<style scoped>
    
</style>