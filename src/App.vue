<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Főoldal</router-link> |
      <router-link to="/about">Hírek</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#nav{
  text-align: center;
}
</style>
