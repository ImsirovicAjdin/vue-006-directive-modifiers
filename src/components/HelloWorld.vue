<template>
  <div class="hello">
    <input v-model.trim="userInput" placeholder="type here">
    <p>You have typed in: {{ userInput }}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      userInput: ""
    };
  }
};
</script>
