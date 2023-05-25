
<script setup lang="ts">
import { defineComponent } from 'vue'
import {useProjects, type projects} from "../model/projects";
import {ref } from 'vue'
import { useRouter } from 'vue-router';



const pointer = ref(0)

function npFit(){
    pointer.value = 1;
}

function tony(){
    pointer.value = 2;
}


function fit(){
    pointer.value = 0;
}

const router = useRouter();











</script>


<template>
    <div class="container is-whole">        
        <nav class="breadcrumb" aria-label="breadcrumbs">
            <ul>
                <li><div class="button" @click="fit">Fitness Tracker</div></li>
                <li><div class="button" @click="npFit">NP Fit</div></li>
                <li><div class="button" @click="tony">Tony's Newburgh Lunch</div></li>
            </ul>
         </nav>
    </div>
    <div v-if="pointer === 0">
    
        <div class="container">
            <div class="columns">
            <div class="column">
               <div class="box is-one">
                <figure class="image is-edit">
                    <img src="../assets/extracker/Screenshot 2023-05-24 at 4.29.20 PM.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="../assets/extracker/Screenshot 2023-05-24 at 4.31.31 PM.png">
                </figure>
                </div>
            </div>
            <div class="column">
                <div class="title">Fitness Tracker</div>
                <hr>
                <div class="title is-5">About the app</div>
                <hr>
                <div class="subtitle">This is a web based application that allows users to track their powerlifting workouts (Bench Press, Squat, and Deadlifts
                    ) as well as cardio runs. Personal Records are a big deal in weightlifting so users can also compare their best lifts to other users on the app to push each other to get stronger.
                     Notifications are sent to the user if they attain a new PR (Personal Record).  </div>
                <hr>
                <div class="title is-5">Technolgy Used</div>
                <hr>
                <div class="subtitle">Frontend: Vue, Typescript, Javascript, Bulma</div>
                <div class="subtitle">Backend: Node, Express</div> 
                <div class="subtitle">Database: MongoDB</div>
                <hr>
                <div class="title is-5">Check out the app</div>
                <hr>
                <div class="subtitle">You can check out this application by clicking <a href="https://exercise-project.onrender.com">Here</a> </div>
            </div> 
        </div>
       </div>
    </div>

    <div v-if="pointer === 1">
    
        <div class="container">
            <div class="columns">
            <div class="column">
               <div class="box is-one">
                <figure class="image is-edit">
                    <img src="../assets/npfit/Screenshot 2023-05-24 at 7.21.03 PM.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="../assets/npfit/Screenshot 2023-05-24 at 7.21.51 PM.png">
                </figure>
                </div>
            </div>
            <div class="column">
                <div class="title">Np Fit</div>
                <hr>
                <div class="title is-5">About the app</div>
                <hr>
                <div class="subtitle">Getting started at the gym is hard, especially when you're in college. Np Fit is an exercise generator app that is specifically designed 
                    for the SUNY New Paltz gym. When users sign up they can decide the level of difficulty of their workouts, and are free to change those settings at any time. Each time the user logs in their daily workout is listed 
                and it is recorded when they finish their workout.   </div>
                <hr>
                <div class="title is-5">Technolgy Used</div>
                <hr>
                <div class="subtitle">Frontend: Vue, Typescript, Javascript, Bulma</div>
                <div class="subtitle">Backend: Node, Express</div> 
                <div class="subtitle">Database: MongoDB</div>
                <hr>
                <div class="title is-5">Check out the app</div>
                <hr>
                <div class="subtitle">You can check out this application by clicking <a href="">Here</a> </div>
            </div> 
        </div>
       </div>

    </div>

    <div v-if="pointer === 2">
    
        <h2> This is the tony's newburgh lunch</h2>

    </div>

   




</template>



<style scoped>

.breadcrumb{
    background-color: transparent;
    color: black;
    padding: 3rem;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    border-radius: 60px;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color:#BCD5D7 ;
    margin-bottom: 1rem;
}
.button{
    background-color: transparent;
    color: black;
    padding: 3rem;
    font-size: 1rem;
    font-weight: 600;
    text-align: center;
    border-radius: 5px;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    border-color: transparent;
  
}

.box{
    border: 0px solid rgb(218, 208, 208);
    color: transparent;
    display: column;
    background-color: #eeeeee;
 
}
.image{
    margin-left: auto;
    margin-right: auto;
    display: block !important;
    border-radius: 50%;
    width: 100%;
    height: 100%;
}
.container{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #eeeeee;

}


</style>