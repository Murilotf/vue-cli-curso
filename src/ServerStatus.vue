<template>
  <div>
    Server Status is: {{ status }}
    <hr>
    <button @click="changeStatus">
      Change Status
    </button>
  </div>
</template>

<script>

export default {
  name: 'Home',
  data: function() {
    return {
      status: 'Normal',
    };
  },
  methods: {
    changeStatus() {
      this.status = 'Critical';
    },
  },
};

</script>

<style>

</style>
