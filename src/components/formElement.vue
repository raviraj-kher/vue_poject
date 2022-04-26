<template>
    <button v-on:click="test()">Click </button>
</template>
<script>
export default {
    name: 'buttonUse',
    methods:{
        test(){
            alert("This is first Button")
        }
    }
}
</script>