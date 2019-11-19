<template>
  <div class="flex-column-x-center app">
    <PageHeader></PageHeader>
    <div class="width-92 home-page-container">
      
    </div>
  </div>
</template>

<script>
import PageHeader from '@/components/Header'
export default {
  name: 'HomePage',
  components:{
    PageHeader
  },
  props:{},
  data(){
    return {
      modulesList: []
    }
  },
  watch:{},
  computed:{},
  methods:{
    
  },
  created(){},
  mounted(){}
}
</script>
<style lang="scss" scoped>
</style>