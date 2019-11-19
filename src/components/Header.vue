<template>
  <div class="app">
    <div class="flex-row-between header">
      <div class="website-name">我才不喜欢哈士奇</div> 
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  components:{},
  props:{},
  data(){
    return {
    }
  },
  watch:{},
  computed:{},
  methods:{},
  created(){},
  mounted(){}
}
</script>
<style lang="scss" scoped>
.app {
  width: 100vw;
  height: 10vh;
}
.header {
  background-color: $baseColor;
  width: 100%;
  height: 100%;
  color: white;
  .website-name {
    margin-left: 5%;
    font-weight: 500;
    font-size: 18px;
  }
}
</style>