<template>
    <div>
        <h1 v-if="show"> Male </h1>
        <h2 v-else> Female </h2>
        <button v-on:click="display">Toggle</button>
    </div>
</template>
<script>
export default {
    name: 'Try2',
    data()
    {
        return{show : false}
    },
    methods:{
        display()
        {
            this.show=!this.show
        }
    }

}
</script>