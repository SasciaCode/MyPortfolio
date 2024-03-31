<template>
<nav class="navbar navbar-expand-lg bg-body-tertiary sticky-top">
  <div class="container-fluid">
      <a class="navbar-brand main d-flex align-items-center" href="#">
        <img src="catlogo.jpg" alt="" class="img-fluid me-2" width="40">
        <p class="fs-3 mt-3   d-none d-lg-block">LAI</p>
      </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" :class="{ 'active text-white': activeLink === 'home' }" @click="activeLink = 'home'" href="#home">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" :class="{ 'active text-white': activeLink === 'projects' }" @click="activeLink = 'projects'" href="#projects">Projects</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" :class="{ 'active text-white': activeLink === 'skills' }" @click="activeLink = 'skills'" href="#skills">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" :class="{ 'active text-white': activeLink === 'contact' }" @click="activeLink = 'contact'" href="#contact">Contact</a>
        </li>
      </ul>
      <p class="fs-3 mt-lg-3 d-none d-lg-block">|</p>
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="git.png" alt="GitHub" width="20">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="fb.png" alt="Facebook" width="20">
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            <img src="twt.png" alt="Twitter" width="20">
          </a>
        </li>
      </ul>
    </div>
  </div>
</nav>

  <div id="home"></div>
  <div class="container-fluid py-4">
    <div class="row">
      <div class="col-lg-6 text-center">
        <img src="profile.png" alt="wow" class="img-fluid py-4">
      </div>
      <div class="col-lg-6 text-center position pt-5">
        <div class="text-lg-start pt-5">
          <p class="main display-1 h-size ms-lg-5">Laimarie</p>
        </div>
        <div class="text-lg-end">
          <p class="main display-1 h-size d-none ms-5 d-lg-block">Bantuas</p>
        </div>
        <div class="text-center py-4">
          <p class="fs-3">At your service!</p>
        </div>
      </div>
    </div>
  </div>

  <div class="container py-4">
    <div class="row">
      <div class="py-2 text-center">
        <p class="display-5 main">
          Allow me to introduce myself...
        </p>
      </div>
      <div class="row">
        <div class="col-lg-6 col-md-12 p-2 text-start">
          <div class="mb-3">
            <label class="form-label">
              Name
            </label>
          <input type="text" class="form-control border-0 shadow bg-white" value="Laimarie Diaz Bantuas" disabled>
          </div>
            <div class="row">
              <div class="col-lg-6 mb-3">
                <label class="form-label">
                  Age
                </label>
              <input type="text" class="form-control border-0 shadow bg-white" value="22 years old" disabled>
              </div>
              <div class="col-lg-6 mb-3">
                <label class="form-label">
                  Birthdate
                </label>
              <input type="text" class="form-control border-0 shadow bg-white" value="March 4, 2002" disabled>
              </div>
            </div>
        </div>
        <div class="col-lg-6 col-md-12 p-2 text-start">
          <div class="mb-3">
            <label class="form-label">
              Address
            </label>
          <input type="text" class="form-control border-0 shadow bg-white" value="Gabi, Cordova, Cebu" disabled>
          </div>
          <div class="mb-3">
            <label class="form-label">
              Current Education Taken
            </label>
          <input type="text" class="form-control border-0 shadow bg-white" value="Bacherlor of Science in Information Technology - Cordova Public College" disabled>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="projects">

  </div>


    <div class="py-2 text-center">
      <p class="display-5 main">
        Projects
      </p>
    </div>


  <div class="container-fluid px-5 py-4">
    <div class="row justify-content-evenly">
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-8">
              <img src="screenshot-1.jpg" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-4">
              <div class="card-body">
                <h1 class="card-title main">Dogs API</h1>
                <p class="card-text text-secondary">API Integration about dogs and their breeds.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-8">
              <img src="screenshot-2.jpg" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-4">
              <div class="card-body">
                <h2 class="card-title main">Smart Dictionary</h2>
                <p class="card-text text-secondary">API Integration for Merriam Webster Dictionary API with supported search and pagination fucnction.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-8">
              <img src="screenshot-3.jpg" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-4">
              <div class="card-body">
                <h1 class="card-title main">Search Song Infos</h1>
                <p class="card-text text-secondary">API Integration provided by Genius Lyrics API with supported search and pagination fucnction.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="skills">

  </div>


    <div class="py-2 text-center">
      <p class="display-5 main">
        Skills
      </p>
    </div>


  <div class="container-fluid px-5 py-4">
    <div class="row justify-content-evenly">
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-4">
              <img src="multi-language.png" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h1 class="card-title main">Knows multiple language</h1>
                <p class="card-text text-secondary">I am fluent in Waraynon, Cebuano, and Filipino. I am also proficient in English</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-4">
              <img src="code.png" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h1 class="card-title main">Knowledgeable in coding</h1>
                <p class="card-text text-secondary">I am familiar with Java, HTML, and CSS. I am also proficient in basic programming concepts and syntax.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-lg-6 py-4">
        <div class="card border-0 shadow mb-3">
          <div class="row g-0 d-flex align-items-center">
            <div class="col-md-4">
              <img src="communicate.png" class="img-fluid rounded-start p-4" alt="...">
            </div>
            <div class="col-md-8">
              <div class="card-body">
                <h1 class="card-title main">Excellence in communication</h1>
                <p class="card-text text-secondary">I have an effective communication and teamwork skills developed through group projects and other school activities.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="contact">

  </div>

  <div class="py-2 text-center">
      <p class="display-5 main">
        Let's talk more!
      </p>
  </div>

  <div class="container-fluid px-5 py-4">
    <div class="row justify-content-evenly">
      <div class="col-lg-3 py-4">
        <a href="" class="text-decoration-none">
          <img src="discord.png" alt="" class="img-fluid" width="50">
          <p class="mt-2 text-dark">SasciaCatto</p>
        </a>
      </div>
      <div class="col-lg-3 py-4">
        <a href="" class="text-decoration-none">
          <img src="msg.png" alt="" class="img-fluid" width="50">
          <p class="mt-2 text-dark">Lai</p>
        </a>
      </div>
      <div class="col-lg-3 py-4">
        <a href="" class="text-decoration-none">
          <img src="tel.png" alt="" class="img-fluid" width="50">
          <p class="mt-2 text-dark">+639693359987</p>
        </a>
      </div>
      <div class="col-lg-3 py-4">
        <a href="" class="text-decoration-none">
          <img src="email.png" alt="" class="img-fluid" width="50">
          <p class="mt-2 text-dark">bantuaslaimarie@gmail.com</p>
        </a>
      </div>
    </div>
  </div>

  <div class="py-2 text-center">
      <p class="display-5 main">
        Follow & interact with me!
      </p>
  </div>

  <div class="container-fluid px-5 py-4">
    <div class="row justify-content-evenly">
      <div class="col-lg-1 py-4">
        <a href="" class="text-decoration-none">
          <img src="ig.png" alt="" class="img-fluid" width="80">
        </a>
      </div>
      <div class="col-lg-1 py-4">
        <a href="" class="text-decoration-none">
          <img src="fb.png" alt="" class="img-fluid" width="80">
        </a>
      </div>
      <div class="col-lg-1 py-4">
        <a href="" class="text-decoration-none">
          <img src="twt.png" alt="" class="img-fluid" width="80">
        </a>
      </div>
      <div class="col-lg-1 py-4">
        <a href="" class="text-decoration-none">
          <img src="git.png" alt="" class="img-fluid" width="80">
        </a>
      </div>
    </div>
  </div>

  <div class="container-fluid mt-5 bg-light" style="--bs-bg-opacity: .5;">
      <div class="row">
          <div class="col-lg-5">
            <h3 class="main fw-bold fs-3 mb-3">
                About this page
            </h3>
            <p> 
              Hey, I'm Lai!, a frontend enthusiast dedicated to crafting immersive user experiences. With expertise in HTML, CSS, and JavaScript, I specialize in bringing designs to life and optimizing interfaces for seamless interaction. Let's collaborate and elevate the web together!
            </p>
          </div>
          <div class="col-lg-4 py-4 d-flex align-items-center left">
            <p class="fs-5">
              © Laimarie Banuas 2024. All rights reserved.
            </p>
          </div>
          <div class="col-lg-2 py-4">
              <h5 class="mb-3">Follow me</h5>
              <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                   Twitter
              </a><br>
              <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                  Facebook
              </a><br>
            <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                 Instagram
              </a><br>
              <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                 Discord
              </a><br>
              <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                 Github
              </a>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      activeLink: 'home'
    };
  }
}
</script>

<style scoped>

h3 {
  margin: 40px 0 0;
}

.h-size {
  font-size: 120px;
}

.main {
  font-family: "Rubik", sans-serif;
  font-optical-sizing: auto;
  font-weight: 600;
  font-style: normal;
}

.position {
  margin-top: 150px;
}

@media only screen and (max-width: 750px) {
  .position {
    margin-top: -180px;
  }

  .h-size {
    font-size: 120px;
  }
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.nav-link {
  border-radius: 20px;
  padding: 8px 15px;
}
.nav-link.active {
  background-color: #eddf8a;
}
</style>
