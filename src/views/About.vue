<template>
  <div class="about">
    <h1>{{name}}</h1>
    <button type="button" @click="test">Click Me</button>
    <Family></Family>

    <Personal></Personal>
    <h1>This is an about page</h1>
  </div>
</template>
<script>
import Family from "../components/about/Family.vue"
import Personal from '../components/about/Personal.vue'
export default {
  name:'about',
  components:{Family,Personal},
  data(){
    return{
       id:this.$route.params.id,
       name:this.$route.params.name,
    }
    },
    methods:{
      test:function(){
        alert(this.name)
      }
    }
}
</script>
<style scoped>

</style>
