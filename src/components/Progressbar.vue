<template>
  <div class="progress-bar">
      <div :class="(progress === 100) ? 'progress-inner complate' : 'progress-inner'" :style="`width: ${ progress }%`">
        <span :class="(progress > 50) ? 'white' : ''">{{ progress }}</span>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Progressbar',
    props: [
        'progress'
    ],
}
</script>

<style scoped>
.progress-bar {
    position: relative;
    width: 100%;
    height: 20px;
    background: #fff;
}
.progress-inner {
    height: 100%;
    background: linear-gradient(to right, #ED009D, #2484E4, #fff);
    border-radius: 0 10px 10px 0;
}
.progress-inner span {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #313131;
    font-size: 14px;
}
.progress-inner .complate {
    border-radius: 0;
}
.progress-inner span.white {
    color: #fff;
}
</style>