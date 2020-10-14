<template>
  <div class="navbar-menu">
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a
            v-bind:href="gitHub"
            target="_blank"
            rel="noopener noreferrer"
          >
            <i class="fab fa-github fa-2x" aria-hidden="true"></i>
          </a>
          <a
            v-bind:href="twitter"
            target="_blank"
            rel="noopener noreferrer"
          >
            <i class="fab fa-twitter fa-2x" aria-hidden="true"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<!-- Modelo -->
<script>
export default {
  name: 'HeaderBarLinks',
  data() {
    return {
      gitHub: 'https://github.com/johnpapa/vue-getting-started',
      twitter: 'https://twitter.com/john_papa'
    }
  },
}
</script>