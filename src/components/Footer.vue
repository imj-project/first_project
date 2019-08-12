<template>
  <div id="footer">
      <span>@2019 vue-project</span>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {

  }
}
</script>


<style>
#footer {
    text-align: right;
    width: 100%;
    height: 40px;
    background-color: pink;
}

span {
    float: right;
    line-height: 1.5;
    padding: 8px 10px;
    vertical-align: middle;
}
</style>