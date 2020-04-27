<template>
  <div class="main">
    <div id="container">
        <nav>
          <header>
            <div class="row text-center">
              <div class="col-md-6">
                  <div class="pr-5 text-white pcb" >SafeSoft PC Cleaner </div>
              </div>
              <div class="col-md-6">
                <div class="text-white us" >United States</div>
              </div>
            </div>
          </header>
      </nav>
      <pcRepair />
    </div>
  </div>
</template>

<script>
import pcRepair from './components/pcRepair.vue'

export default {
  components: {
    pcRepair
  }
}
</script>

<style scoped>
  #container {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #2c3e50;
    max-width: 100%;
    padding: 0;
  }
  
  nav {
    background: #2992b8;
     padding: 15px;
  }
  .text-white {
    font-size: 20px;
    font-weight: 500;
  }
.pcb {
  position: relative;
  left: 9px;
}
.text-white.us {
    margin-left: 73px;
}

  
</style>
