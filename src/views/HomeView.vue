<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div>
  <button class="btn btn-success" @click="goToDayBook">Success</button>
</template>

<script>
export default {
  methods: {
    goToDayBook() {
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>
