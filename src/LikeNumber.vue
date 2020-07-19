<template>
  <div>
    <p>いいね({{ number }})</p>
    <button @click="Up">+1</button>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      number: 5
    };
  },
  methods: {
    Up() {
      this.number += 1;
    }
  }
};
</script>