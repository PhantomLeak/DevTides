<template>
  <div class="footer">
    <div style="width: 100%; text-align: center;">
      <span>©{{ year }} All Rights Reserved. A side project by Dylan Stocking & Cole Weegar.</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
}

</script>

<style scoped>
.footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  border: 1px solid black;
}
</style>