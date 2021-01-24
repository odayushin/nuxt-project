<template>
  <div>
    <h1>Hello world!</h1>
    <button v-on:click="turn">隠しエリア</button>
    <div v-if="isMessageOk">隠しエリアだよー</div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isMessageOk: true,
    };
  },
  methods() {
    return {
      turn: function () {
        this.isMessageOk = !this.isMessageOk;
      },
    };
  },
};
</script>