<template>
  <!-- <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav> -->
  <router-view class="text-light mt96" />
</template>

<style lang="scss">
@import './assets/stylesheets/all.scss';
body {
  background-color: #0e1621;
  padding: 0;
}

.mt96 {
  margin-top: 96px;
}
</style>

