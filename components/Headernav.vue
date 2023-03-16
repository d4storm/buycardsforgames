<template>
  <div class="headernav">
    <div class="logoholder">
      <img src="../assets/imgs/logo.png" alt="Buy Game Cards" class="logo" />
      <Links />
    </div>
  </div>
</template>

<script>
export default {
  name: 'headernav',
}
</script>

<style lang="scss" scoped>
.headernav {
  width: 100%;
  
}
.logo{
  height:80px;
  float:left;
}
.logoholder {
  float:left;
  width:100%;
  top: 10px;
  position: absolute;
  z-index: 999;
  background-color: rgba(238, 5, 28, 0.616);
}


</style>
