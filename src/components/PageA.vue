<template>
  <div>
    <h1>Page A</h1>
    <p>Article {{ $route.params.id }}</p>
    <ul>
      <router-link :to="{name: 'a.b'}">Voir la vue B</router-link>
      <router-link :to="{name: 'a.c'}">Voir la vue C</router-link>
    </ul>
    <h2>Sous-vue</h2>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  
}
</script>