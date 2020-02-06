<template>
  <div class="container">
    <h1>Lasse D. Spilling</h1>
    <a href="https://vg.no" class="vg">Read newspaper</a>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
body {
  background: #e8f8ff;
}
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  flex-direction: column;
}

.vg {
  letter-spacing: 0.05rem;
  margin: 1rem;
  display: block;
  transform: scale(.9);
  transition: all .2s ease;
  background: red;
  font-family: system-ui;
  text-decoration: none;
  color: white;
  font-weight: bold;
  padding: .5rem 1rem;
  border-radius: 1rem;
}
.vg:hover {
  transform: scale(1);
  letter-spacing: 0.1rem;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
