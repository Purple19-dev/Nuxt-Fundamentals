<template>
  <section class="container">
    <div>
      <Hero/>
      <h1 class="title">Black COder</h1>
      <h2 class="subtitle"> MY first Nuxt.js project</h2>
      <div class="links">
        <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation <IconLink/></a>
        <NLink to="/about" class="button--grey">About</NLink>
      </div>
    </div>
  </section>
</template>

<script>
import Hero from '~/components/Hero.vue'

export default {
  components: {
    Hero
  }
}
</script>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #2E495E;
  letter-spacing: 1px;
  font-size: em;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
