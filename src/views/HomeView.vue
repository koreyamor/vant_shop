<template>
  <div class="home">
    <van-search v-model="SearchVal" shape="round" placeholder="请输入搜索关键词" disabled/>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "HomeView",
  data(){
    return{
      SearchVal:""
    }
  },
  components: {},
};
</script>
