<script setup lang="ts"></script>

<template>
  <section class="section">
    <br />
    <h1 class="title">Welcome!</h1>
    <h2 class="subtitle">Hello my name is Thomas Coffey</h2>
  </section>
  <div class="c">
    <div class="columns">
      <div class="column">
        <div class="box is-info">
          <div class="container">
            <figure class="image is-rounded is-128x128">
              <img
                class="is-rounded"
                src="https://i.postimg.cc/cHZcff1z/IMG-0028-Small.jpg"
              />
            </figure>
            <br />
            <br />
            <p class="title is-5">About Me</p>
          </div>

          <hr />
          <p class="subtitle is-6">
            I am a recent graduate from SUNY New Paltz with a Bachelor's Degree
            in Computer Science. I am currently looking for a full-time position
            as a Software Engineer. I am passionate about learning new
            technologies and working on projects that will help me grow as a
            developer. I have experience in full-stack development and web
            development. I am currently learning about cloud computing and
            machine learning in my spare time.
          </p>

          <div class="box is-github">
            <i class="fab fa-github"></i>
            <a href="https://www.github.com/tomtomcoffey">Github </a>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <i class="fab fa-linkedin"></i>
            <a href="https://www.linkedin.com/in/thomas-coffey-26464a114/"
              >Linkedin</a
            >
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <i clss=" fab fas-email"></i>
          </div>
        </div>
      </div>
      <div class="column is-edit">
        <div class="box is-info">
          <p class="title is-5">Education</p>
          <hr />
          <p class="subtitle is-6">
            The State University of New York at New Paltz
          </p>
          <p class="subtitle is-6">Bachelor of Science in Computer Science</p>
          <p class="subtitle is-6">GPA: 3.71</p>
          <p class="subtitle is-6">Graduated December 2023</p>
        </div>

        <div class="column is-right">
          <div class="box is-info">
            <p class="title is-5">Skills</p>
            <hr />
            <p class="subtitle is-6">
              <strong>Languages:</strong> Java, Typescript , Javascript, C, C#,
              Python, Javascript, HTML, CSS
            </p>
            <p class="subtitle is-6">
              <strong>Frameworks:</strong> Vue, React, Node, Express, Flask,
              Django, Bulma, Bootstrap
            </p>
            <p class="subtitle is-6">
              <strong>Databases:</strong> MySQL, MongoDB
            </p>
            <p class="subtitle is-6">
              <strong>Tools:</strong> Git, Docker, Postman, VS Code, IntelliJ
            </p>
          </div>

          <div class="box is-info">
            <p class="title is-5">Contact</p>
            <hr />
            <p class="subtitle is-6">
              <strong>Email: </strong>tomcoffey1017@gmail.com
            </p>
            <p class="subtitle is-6"><strong>Phone: </strong>845-863-6371</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.image {
  margin-top: -20px;
  margin-left: -30px;
}

.box {
  margin-top: 5%;
  margin-bottom: 5%;
}

.section {
  background-image: linear-gradient(to right, #f5f7fa, #c3cfe2);
}

.column {
  background-color: #f5f7fa;
}

.title {
  font-size: 2rem;
  font-weight: 600;
  font: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}

.subtitle {
  font-size: 1rem;
  margin-top: 3px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
</style>
