<template>
  <div id="app">
    <input v-model="message" placeholder="edit me" />
    <p>Message is: {{ message }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      message: "",
    };
  },
};
</script>