<template>
  <header>
    <router-link class="link" :to="{ name: 'home' }">Home</router-link>
    <router-link class="link" to="/categorias">Categorias</router-link>
    <router-link class="link" to="/marcas">Marcas</router-link>
    <router-link class="link" to="/acessorios">Acessorios</router-link>
    <router-link class="link" to="/cores">Cores</router-link>
  </header>
  <main>
    <RouterView />
  </main>
</template>

<style>
.link{
  padding: 10px;
}
</style>