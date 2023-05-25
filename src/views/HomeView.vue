<script setup lang="ts">

</script>

<template>
  <section class="section is-info">
    <!-- <figure class="image is-64x64">
  <img src="../assets/tom.png">
</figure> -->
 
</section>

   <div class="columns">
      <div class="column is-left">
        <div class="box is-info">
         <p class="title is-5">  About me</p>
         <hr>
         <p class="subtitle is-6">I am currently a student at The State University of New York at New Paltz pursing a Bachelor's degree in Computer Science. I am currently in my senior year   </p>
     </div>


    <div class="box is-info">
      <p class="title is-5"> Education </p>
      <hr>
      <p class="subtitle is-6">The State University of New York at New Paltz</p>
      <p class="subtitle is-6">Bachelor of Science in Computer Science</p>
      <p class="subtitle is-6">GPA: 3.72</p>
      <p class="subtitle is-6">Expected Graduation: Dec 2023</p>
    </div>


    <div class="box is-info">
      <p class="title is-5">Contact</p>
      <hr>
      <p class="subtitle is-6">Email: coffeyt1@newpaltz.edu</p>
      <p class="subtitle is-6">Phone: 845-863-6371</p>

  </div>
  </div>
  <div class="column is-right">
    <div class="box is-info">
      <p class="title is-5">Skills</p>
      <hr>
      <p class="subtitle is-6">Languages: Java, Typescript , Javascript, C, C#, Python </p>
      <p class="subtitle is-6">Frameworks: Vue, React, Node, Express, Flask, Django, Bulma  </p>
      <p class="subtitle is-6">Databases: MySQL, MongoDB </p>
      <p class="subtitle is-6">Tools: Git, Docker, AWS, Azure, Google Cloud </p>

    </div>
    <div class="box is-info">
      <p class="title is-5"> Experience </p>
      <hr>
    
     
      

    </div>
  
      
    
  </div>
 
</div>

    

</template>

<style scoped>
.column {
    
    padding: 10px;

    border-radius: 5px;
    background-color: transparent;
    display: block;
    scroll-behavior: auto;
}

.section{
    margin-top: 10px;
    margin-bottom: 10px;
    margin-left: 10px;
    margin-right: 10px;
    padding: 10px;
    border-radius: 5px;
    background-color: transparent;
    display: block;
}
.box{
    border: 0px solid rgb(218, 208, 208);
    color: transparent;
 
}


.image{
    margin-left: auto;
    margin-right: auto;
    display: block !important;
    border-radius: 50%;
}

.column.is-left{
    
    border: 1px solid rgb(218, 208, 208);
    border-radius: 5px;
    background-color: #f5f5f5;
    display: block;
}
.column.is-right{

    border: 1px solid rgb(218, 208, 208);
    border-radius: 5px;
    background-color: #BCD5D7;
    display: block;

}

.title{
  font: 400 1.5rem/1.5rem 'Roboto', sans-serif;
}
.subtitle{
  font: 400 1.2rem/1.2rem 'Roboto', sans-serif;
}


</style>
