<template>
  <div id="app">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/news">News</RouterLink>
      </nav>

      <main>
        <RouterView></RouterView>
      </main>
  </div>
</template>

<script>

export default {};
</script>

<style>

</style>
