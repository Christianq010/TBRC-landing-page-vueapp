<template>
  <div class="home">
    <home-page />
  </div>
</template>

<script>
// @ is an alias to /src
import HomePage from '@/components/HomePage.vue'

export default {
  name: 'home',
  components: {
    HomePage
  }
}
</script>
