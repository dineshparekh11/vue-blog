<template>
    <div>
        <button v-on:click="updateTitle">Update Parent title</button>
    </div>
</template>

<script>
    export default{
        name:'Child',
        methods:{
            updateTitle(){
                this.$emit('changeTitle','Parent updated')
            }
        }
}
</script>