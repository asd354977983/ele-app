<template>
<sub-page class="subpage" :id="pageId">

</sub-page>
</template>

<script>
  import SubPage from '../../common/SubPage.vue'
  export default{
      components:{
          [SubPage.name]:SubPage
      }
  }
</script>

<style>
  .subpage{
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0px;
    z-index: 5;
  }
</style>
