<template>
<div>
TestComp-rollup-test1.0.1
{{testmsg}}
<p @click="add">add</p>
 </div>
</template>

<script>
 export default {
    name: 'TestRollup',
    data(){
        return{
            count:1
        }
    },
    computed:{
      testmsg(){
        return this.count*2
      }
    },
    methods:{
      add(){
         this.count++
      }
    }
  }
</script>

<style lang='scss' scoped>

</style>