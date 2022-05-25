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

        }
    },
    created() {
        
    }
}
</script>
<style scoped>
    
</style>