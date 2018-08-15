<template>
<nav class="navbar has-shadow is-spaced">
  <div class="navbar-brand">
      <router-link class="navbar-item" to="/">
      <img src="https://bulma.io/images/bulma-logo.png" alt="Bulma: a modern CSS framework based on Flexbox" width="112" height="28">
      </router-link>
    <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

  <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-start">
      <router-link class="navbar-item" to="/about">About Us</router-link>
      <router-link class="navbar-item" to="/signup">Become a Tutor</router-link>
      <router-link class="navbar-item" to="/request">Get a Tutor</router-link>
      <router-link class="button is-primary is-rounded" to="/login">Login</router-link>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="field is-grouped">
          
          <p class="control">
            <a class="bd-tw-button button" data-social-network="Twitter" data-social-action="tweet" data-social-target="#" target="_blank" href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://localhost:4000&amp;via=jgthms">
              <span class="icon">
                <i class="fab fa-twitter"></i>
              </span>
            </a>
          </p>
          <p class="control">
           <a class="bd-tw-button button" data-social-network="Twitter" data-social-action="tweet" data-social-target="#" target="_blank" href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://localhost:4000&amp;via=jgthms">
              <span class="icon">
                <i class="fab fa-facebook"></i>
              </span>
            </a>
          </p>
           <p class="control">
           <a class="bd-tw-button button" data-social-network="Twitter" data-social-action="tweet" data-social-target="twitter.com" target="_blank" href="https://twitter.com/intent/tweet?text=Bulma: a modern CSS framework based on Flexbox&amp;hashtags=bulmaio&amp;url=http://localhost:4000&amp;via=jgthms">
              <span class="icon">
                <i class="fab fa-instagram"></i>
              </span>
            </a>
          </p>
        </div>
      </div>
    </div>
  </div>
</nav>
</template>
<<script>
  export default {
    name: 'Header',

      data() {
          return {
              title: 'Prep Me'
          }
      },
      methods: {
      
      },
    
  }  
</script>
<style scoped>
    
</style>