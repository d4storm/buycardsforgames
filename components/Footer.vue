<template>
  <div class="footer">
    <hr>
      <Links />
  </div>
</template>

<script>
export default {
  name: 'footer',
}
</script>

<style lang="scss" scoped>

  hr {
  border: none;
  border-top: 1px solid rgba(255,255,255,.3);
  border-bottom: 1px solid rgba(0,0,0,.08);
  margin: 2.1em 0;
  position: relative;
}


.footer {
  width:100%;
  padding:20px;
  margin:20px 0px;
}


</style>
