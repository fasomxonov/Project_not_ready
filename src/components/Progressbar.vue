<template>
  <div class="progress-bar">
      <div class="progress-inner">
        <span>0%</span>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.progress-bar {
    width: 100%;
    height: 20px;
    background: #fff;
}
.progress-inner {
    height: 100%;
    background: linear-gradient(to right, #ED009D, #2484E4);
    border-radius: 0 10px 10px 0;
}
</style>