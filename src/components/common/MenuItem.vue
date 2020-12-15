<template>
  <div>
    <a class="header" href="#">{{ text }}</a>
  </div>
</template>

<script>
export default {
name: "MenuItem",
  props:{
    text: {
      type: String
    }
  }
}
</script>

<style scoped>

</style>