<script setup lang="ts"></script>

<template>
  <section class="hero is-fullheight is-primary">
    <div class="hero-body">
      <div class="container">
        <h1 class="title1 is-1">Welcome!</h1>
        <h2 class="subtitle1 is-3">Hello, my name is Thomas Coffey</h2>
      </div>
    </div>
  </section>

  <div class="container mt-5">
    <div class="columns">
      <div class="column is-one-third">
        <div class="card has-background-info-light">
          <div class="card-content">
            <div class="media">
              <div class="media-left">
                <figure class="image is-128x128">
                  <img
                    class="is-rounded"
                    src="https://i.postimg.cc/cHZcff1z/IMG-0028-Small.jpg"
                    alt="Profile Image"
                  />
                </figure>
              </div>
              <div class="media-content">
                <p class="title is-4 has-text-info">About Me</p>
                <div class="content">
                  <p>
                    I am a recent graduate from SUNY New Paltz with a Bachelor's
                    Degree in Computer Science. Currently seeking a full-time
                    position as a Software Engineer.
                  </p>
                  <p>
                    Passionate about learning new technologies and working on
                    projects that will help me grow as a developer. Experience
                    in full-stack development and web development.
                  </p>
                  <p>
                    Currently learning about cloud computing and machine
                    learning in my spare time.
                  </p>
                </div>
              </div>
            </div>

            <hr class="my-3" />

            <div class="social-icons">
              <a href="https://www.github.com/tomtomcoffey" target="_blank">
                <i class="fab fa-github fa-2x"></i>
              </a>
              <a
                href="https://www.linkedin.com/in/thomas-j-coffey/"
                target="_blank"
              >
                <i class="fab fa-linkedin fa-2x"></i>
              </a>
              <!-- Add other social icons as needed -->
            </div>
          </div>
        </div>
      </div>

      <div class="column">
        <div class="card has-background-info-light">
          <div class="card-content">
            <p class="title is-4 has-text-info">Education</p>
            <div class="content">
              <p>The State University of New York at New Paltz</p>
              <p>Bachelor of Science in Computer Science</p>
              <p>GPA: 3.71</p>
              <p>Graduated December 2023</p>
            </div>
          </div>
        </div>

        <div class="card has-background-info-light mt-3">
          <div class="card-content">
            <p class="title is-4 has-text-info">Skills</p>
            <div class="content">
              <p>
                <strong>Languages:</strong> Java, Typescript, Javascript, C, C#,
                Python, HTML, CSS
              </p>
              <p>
                <strong>Frameworks:</strong> Vue, React, Node, Express, Flask,
                Django, Bulma, Bootstrap
              </p>
              <p><strong>Databases:</strong> MySQL, MongoDB</p>
              <p>
                <strong>Tools:</strong> Git, Docker, Postman, VS Code, IntelliJ
              </p>
            </div>
          </div>
        </div>

        <div class="card has-background-info-light mt-3">
          <div class="card-content">
            <p class="title is-4 has-text-info">Contact</p>
            <div class="content">
              <p><strong>Email:</strong> tomcoffey1017@gmail.com</p>
              <p><strong>Phone:</strong> 845-863-6371</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero {
  background-image: linear-gradient(to right, #869fa1 0%, #cccccc 100%);
}

.title,
.subtitle {
  color: #000405 !important;
}

.card {
  border-radius: 15px;
}

.card-content {
  padding: 2rem;
}

.social-icons a {
  color: #3498db;
  margin-right: 1rem;
  transition: color 0.3s ease-in-out;
}

.social-icons a:hover {
  color: #2980b9;
}

.has-background-info-light {
  background-color: #f5f7fa !important;
}

.title1 {
  font-size: 3rem;
  font-weight: 600;
  color: #ecf0f1 !important;
}

.title2 {
  font-size: 2rem;
  font-weight: 600;
  color: #ecf0f1 !important;
}

@media screen and (max-width: 768px) {
}
</style>
