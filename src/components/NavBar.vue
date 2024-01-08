<script setup lang= "ts">
import { ref } from 'vue';
import { RouterLink, RouterView } from 'vue-router';

const isMenuActive = ref(false);

</script>

<template>

<nav class="navbar is-info">
    <div class="container">
        <div class="navbar-brand">
    
            
  
            
     
          <div class="navbar-burger" :class="{ 'is-active': isMenuActive }" @click="isMenuActive = !isMenuActive" >
            <span></span>
            <span></span>
            <span></span>
          </div>
        </div>
      
        <div class="navbar-menu" :class="{ 'is-active': isMenuActive }">
          <div class="navbar-start">
            

   


    
          </div>
      
          <div class="navbar-end">
            <div class="navbar-item">
              <div class="field is-grouped">
                <RouterLink to="/" class="navbar-item">Profile</RouterLink>
                <RouterLink to="/projects" class="navbar-item">Projects</RouterLink>
                 <RouterLink to="/resume" class="navbar-item">Resume</RouterLink>
              </div>
            </div>
          </div>
        </div>
        </div>
      </nav>
 

</template>

<style scoped>


.navbar{
                    background-color: whitesmoke;
            }
            .navbar-item{
                font-size: 1rem;
                font-weight: 600;
            }
            .navbar-item:hover{
                background-color: whitesmoke;
            }
            .navbar-item:active{
                background-color: whitesmoke;
            }
            .navbar-item:focus{
                background-color: whitesmoke;
            }
            .navbar-item:visited{
                background-color: whitesmoke;
            }
            .navbar-item:link{
                background-color: whitesmoke;
            }
           
          
.navbar-burger{
  background-color: rgb(32, 31, 31);
  color: rgb(60, 59, 59);
}



</style>