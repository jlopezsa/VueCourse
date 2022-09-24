<template>
  <div>
    <h1>Example with variables {{ message }}</h1>
    <ul>
      <li>String: {{ message }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "VariablesComponent",
  setup() {
    const message = "String example valiable";
    return {
      message,
    };
  },
};
</script>
