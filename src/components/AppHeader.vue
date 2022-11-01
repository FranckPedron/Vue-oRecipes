<template>
  <header class="header">
    <router-link to="/">
      <img src="src/assets/logo.png" class="header-logo" alt="Logo oRecipes"/>
    </router-link>
  </header>
</template>

<script>
import "../styles/_vars.scss";
export default {
  name: "AppHeader"
}
</script>

<style lang="scss">
@use '../styles/vars';
.header {
  padding: vars.$halfGutter vars.$gutter;
  box-shadow: 0 20px 20px -30px rgba(0, 0, 0, .4);
  text-align: center;
  display: flex;
  justify-content: space-between;
  align-items: center;

  &-logo {
    width: 50px;
  }
}
</style>
