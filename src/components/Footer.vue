<template>
  <footer>
  <nav>
  <router-link to="/about">About</router-link>
    <span></span>
  <router-link to="/privacypolicy">Privacy Policy</router-link>
</nav>
    <p>Copyright &copy; {{year}} </p>
  </footer>
</template>
<script>
import { computed } from 'vue'

export default {
  setup () {
    const year = computed(() => new Date().getFullYear())
    return {year}
  }
}
</script>