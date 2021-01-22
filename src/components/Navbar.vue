<template>
  <div class="Navbar">
    <nav class="navbar navbar-expand-lg navbar-light bg-dark">
      <a class="navbar-brand text-light" href="#">
        <img class="short" src="../assets/img/TDLogo.png" alt="">
      </a>
      <button class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarNavAltMarkup"
              aria-controls="navbarNavAltMarkup"
              aria-expanded="false"
              aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <a class="text-light nav-item nav-link active" href="#"> <router-link class="text-light" :to="{name: 'Home'}">
            Home
          </router-link><span class="sr-only">(current)</span></a>
          <a class="text-light nav-item nav-link" href="#">
            <router-link class="text-light" :to="{name: 'About'}">About</router-link>
          </a>
          <a class="text-light nav-item nav-link" href="#"><router-link class="text-light" :to="{name: 'Projects'}">Projects</router-link></a>
          <a class="text-light nav-item nav-link" href="#"><router-link class="text-light" :to="{name: 'Contact'}">Contact</router-link></a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  setup() {
    return {}
  },
  components: {}
}
</script>

<style lang="scss" scoped>
.short{
  max-height: 10%;
  width: auto;
}

</style>
