<template>
  <div>
      <nav class="navbar navbar-expand-md navbar-dark bg-dark ">
          <div class="container">
              <router-link to="/" class="navbar-brand">Logo </router-link>
               <ul class="navbar-nav">
              <li><router-link :to="{name:'Home',params:{id:1,name:'sajib'}}" class="nav-link">Home</router-link></li>
              <li><router-link :to="{name:'About',params:{id:2,name:'bhuyan'}}" class="nav-link">About</router-link></li>
              <li><router-link :to="{name:'service',params:{id:3,name:'mehedi'}}" class="nav-link">Service</router-link></li>
              <li><router-link to="/contact" class="nav-link">Contact</router-link></li>
          </ul>

          </div>
         
      </nav>
  </div>
    
</template>
<script>
export default {
    name:'Navbar'
}
</script>
<style>
</style>