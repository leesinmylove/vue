<template>
  <div class="hello">
    <span>hello red</span>
    <div class="msg">{{msg}}</div>
  </div>
</template>

<script>
export default {
  props: ['srcs'],
  data () {
    return {
      msg: 'hello yellow'
    }
  },
  computed: {
  },
  watch: {
  },
  created () {

  },
  mounted () {
  },
  methods: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.hello {
  color: red;
  .msg {
    color: aqua;
  }
}
</style>
