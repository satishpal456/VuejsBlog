<template>
  <div>
  <div><midd></midd></div>
  </div>
</template>

<script>
  import middlesite from './middlesite.vue'
export default {

  data () {
    return {
     head:"satish Pal"
    }
  },
  components:{
    'midd':middlesite
  }
}
</script>

<style scoped>
#h{
  background:linear-gradient(to left,lightgreen,goldenrod);
}

</style>
