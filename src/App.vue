<template>
  <main>
    <button :id="mainh2" @click="changeId">What's 9+10</button>
  </main>
</template>

<script>
export default {
  methods: {
    changeId() {
      this.id = blue;
    }
  }
}
  
</script>

<style>
.button #blue {
  background-color: blue;
}

#mainh2 {
  background-color: red;
}

</style>