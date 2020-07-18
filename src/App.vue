<!-- ================ Template ================================================ -->
<template lang="pug">
#app
  h1 My name's: {{name}}
</template>

<!-- ================ Script ================================================ -->
<script>
export default {
  data: () => ({ name: `Sara`, age: 20 }),
}
</script>

<!-- ================ Style =============================================== -->
<style lang="scss" scoped></style>
