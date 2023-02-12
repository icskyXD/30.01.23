<script>
export default {
}
</script>

<template>
  <header>
    <a href="/gallery">Gallery</a>
    <a href="/home">Main</a>
    <a href="/contacts">Contact</a>
  </header>
  <router-view/>
</template>

<style>
  header {
    display: flex;
    flex-direction: column;
  }
</style>