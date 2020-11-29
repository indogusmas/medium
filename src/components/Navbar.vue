<template> 
 <nav class="navbar navbar-light">    
   <div class="container">      
     <a class="navbar-brand" href="index.html">Medium Clone</a>      
     <ul class="nav navbar-nav pull-xs-right">        
       <li class="nav-item">
       <router-link class="nav-link" :to="{name : 'Home'}">Home</router-link>
      </li>       
      <li class="nav-item">          
       <a class="nav-link" href="">           
        <i class="ion-compose"></i>&nbsp;New Post  
       </a>        
      </li>
      <li class="nav-item">
       <router-link class="nav-link" :to="{name : 'Setting'}">Setting</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link" :to="{name : 'Login'}">Sign In</router-link>
      </li>
      <li class="nav-item">
       <router-link class="nav-link" :to="{name : 'Register'}">Sign Up</router-link>
      </li>
     </ul>
    </div>
  </nav>                  
</template>
<script>
export default {
    name:'Navbar'
}
</script>

<style scoped>

</style>