<template>
      <ul class="nav">
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About us</NuxtLink></li>
        <li><a href="">How to buy Game Card or Movie</a></li>
        <li><a href="">Privacy and policy</a></li>
        <li><a href="">Money back guarantee</a></li>
      </ul>
</template>

<script>
export default {
  name: 'links',
}
</script>

<style lang="scss" scoped>

.nav li {
  float: left;
  display: flex;
  padding: 5px 10px;
}

.nav li a {
  text-decoration: none;
  color: inherit;
  color: #fff;
  cursor: pointer;
  transition: 0.3s ease all;

  &:hover {
    text-decoration: underline;
    color: rgb(55, 244, 13);
  }
}
</style>

