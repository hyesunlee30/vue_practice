<template>
  <nav>
    <router-link to="/basic">Basic</router-link> |
    <router-link to="/databinding">DataBinding</router-link> |
    <router-link to="/databindinghtml">DataBindingHtml</router-link> |
    <router-link to="/databindinginputtext">DataBindingInputText</router-link> |
    <router-link to="/databindingexample">Example</router-link> |
    <router-link to="/list">List</router-link> |
    <router-link to="/render">Render</router-link> |
    <router-link to="/event">Event</router-link> |
    <router-link to="/computed">Computed</router-link> |
    <router-link to="/watch">Watch</router-link> |
    <router-link to="/search">Search</router-link> |
    <router-link to="/save">Save</router-link> |
    <router-link to="/server">ServeData</router-link> |
    <router-link to="/slot">SlotUseModalLayout</router-link> |
    <router-link to="/provide">Provide Inject</router-link> |
    <router-link to="/mixin">Mixin</router-link> |
    <router-link to="/calculator">Calculator</router-link> |
    <router-link to="/com1">CompositionAPI1</router-link> |
    <router-link to="/com2">CompositionAPI2</router-link> |
    <router-link to="/com3">CompositionAPI3</router-link> |
    <router-link to="/com4">CompositionAPI4</router-link> |
    <router-link to="/com5">CompositionAPIProvideInjection</router-link> |
    <router-link to="/customdirective">CustomDirective</router-link> |
    <router-link to="/plugins">Plugins</router-link> |
    <router-link to="/storeaccess">storeaccess</router-link>
  </nav>
  <router-view />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
