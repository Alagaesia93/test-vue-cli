<template>
  <div id="app">
    <p>{{ message }} </p>
    <input type="text" v-model="message">
  </div>
</template>

<script>

export default {
  name: 'app',
  data() {
    return {
      message: '',
    };
  },
};
</script>
