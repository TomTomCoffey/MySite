
<script setup lang="ts">
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

function bert(){
    pointer.value = 3;

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
                <li><div class="button" @click="bert">Question Answering System</div></li>
            </ul>
         </nav>
    </div>
    <div v-if="pointer === 0">
    
        <div class="container">
            <div class="columns">
            <div class="column">
               <div class="box is-one">
                <figure class="image is-edit">
                    <img src="../assets/extracker/extrackerStats.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="../assets/extracker/extrackerGraph.png">
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
                    <img src="https://i.postimg.cc/jdz3nqhC/Screenshot-2023-05-24-at-7-21-03-PM.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="https://i.postimg.cc/mgmw7P1Z/Screenshot-2023-05-24-at-7-21-51-PM.png">
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
                <div class="subtitle">You can check out this application by clicking <a href="https://np-fit-app.onrender.com">Here</a> </div>
            </div> 
        </div>
       </div>

    </div>

    <div v-if="pointer === 2">
    
        <div class="container">
            <div class="columns">
            <div class="column">
               <div class="box is-one">
                <figure class="image is-edit">
                    <img src="../assets/newburghlunch/tony.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="../assets/newburghlunch/menu.png">
                </figure>
                </div>
            </div>
            <div class="column">
                <div class="title">Tony's Newburgh Lunch Website</div>
                <hr>
                <div class="title is-5">About the project</div>
                <hr>
                <div class="subtitle">This was my first ever paid project. I was tasked with creating a user friendly website to improve customer traffic </div>
                <hr>
                <div class="title is-5">This project is finished </div>
                <hr>
                <div class="subtitle">Check out my work by clicking <a href="http://www.tonysnewburghlunch.com/index.php">Here</a> </div>
            </div> 
        </div>
       </div>

    </div>

    <div v-if="pointer===3">

        <div class="container">
            <div class="columns">
            <div class="column">
               <div class="box is-one">
                <figure class="image is-edit">
                    <img src="../assets/qa.png">
                </figure>
                <br>
                <figure class="image is-edit">
                    <img src="../assets/answer.png">
                </figure>
                </div>
            </div>
            <div class="column">
                <div class="title">Question Answering System</div>
                <hr>
                <div class="title is-5">About the project</div>
                <hr>
                <div class="subtitle">This was a project I developed which uses the BERT natural language processing model to answer questions based on either the Wikipedia API, or through the system's built in Webcrawler</div>
                <hr>
                <div class="title is-5">Technolgy Used</div>
                <hr>
                <div class="subtitle">Pytorch, Transformers, Python, Javascript, HTML, CSS, PHP </div>
                <hr>

                <div class="title is-5">This project is finished </div>
                <hr>
                <div class="subtitle">Check out my work by clicking <a href="http://cs.newpaltz.edu/p/f23-03/v3/index.php">Here</a> </div>
            </div> 
        </div>
       </div>
       
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
    flex-direction: row;
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