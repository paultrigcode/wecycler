<template>
  <div class="hello">
    <dashboard> </dashboard>
  
  </div>
</template>

<script>

import dashboard from '@/components/dashboard.vue';


export default {

  components:{
  
    'dashboard':dashboard,
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">

</style>
