<template>
<div>
 <p> server status: {{ status }} </p>
 <hr>
 <button @click="changeStatus"> Change </button>
</div>
</template>

<script>
export default {
  data: function() {
    return {
      status: 'Critical'
    }
  },
  methods: {
    changeStatus() {
      this.status = 'Normal';
    }
  }
}
</script>

<style>
</style>
