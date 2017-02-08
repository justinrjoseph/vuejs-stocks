<template lang="html">
  <div>
    <h1>Manage your Portfolio</h1>
    <h4>Save &amp; Load your Data</h4>
    <h6>Use <strong>End Day</strong> to begin a New Day!</h6>
    <hr>
    <p>Funds: {{ funds | currency }}</p>
  </div>
</template>

<script>
  export default {
    computed: {
      funds() {
        return this.$store.getters.funds;
      }
    }
  }
</script>

<style lang="css">
</style>
