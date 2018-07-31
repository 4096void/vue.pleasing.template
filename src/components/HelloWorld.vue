<template lang="jade">
  .helloworld hello world!_
</template>
<script>
export default {
  data() {
    return {};
  },
};
</script>
<style lang="stylus">
colors(bg, clr)
  background bg
  color clr

html
  colors(black, lime)

.helloworld
  font-size 1rem
</style>
