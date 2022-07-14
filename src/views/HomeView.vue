<template>
  <main>

    <Dashboard />
    
  </main>
</template>

<script>
import Dashboard from '../components/Dashboard.vue'
  export default {
    components:{Dashboard}
  }
</script>

<style>
  /* Custom style */
  .header-right {
      width: calc(100% - 3.5rem);
  }
  .sidebar:hover {
      width: 16rem;
  }
  @media only screen and (min-width: 768px) {
      .header-right {
          width: calc(100% - 16rem);
      }        
  }
</style>
