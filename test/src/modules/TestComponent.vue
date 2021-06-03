<template>
  <div>
    テストです。
    {{ testData }}
  </div>
</template>

<script>
export default {
  name: "TestComponent",
  data() {
    return {
      testData: "テストデータです。",
    };
  },
};
</script>

<style>
</style>