<style src="./home.css"></style>
<template>
  <div id="app">
    <div class="main">
      <div class="container">
        <div class="profile">
        </div>
        <div class="title">
          <h1 class="title-name">Deven Rathod</h1>
          <p>
            Full Stack Developer <br />
            <a
              href="https://service.developerspot.in/"
              target="https://service.developerspot.in"
              ><span class="highlight-text">@DeveloperSpot</span></a
            >
          </p>
        </div>
        <div class="social-container">
          <button
            class="github comn-button"
            onClick="location.href='https://github.com/devenrathod2'"
          >
            I'm On GitHub
          </button>
          <button
            class="twitter comn-button"
            onClick="location.href='https://twitter.com/IamDevenR'"
          >
            I'm Also on Twitter
          </button>
          <button
            class="linkedin comn-button"
            onClick="location.href='https://linkedin.com/in/devenrathod'"
          >
            Let's Make Connection
          </button>
          <button
            class="instagram comn-button"
            onClick="location.href='https://instagram.com/devenrathod.me'"
          >
            Follow Me On Instagram
          </button>

          <div class="footer-text">
            <p>
              Design with <span class="highlight-text-red">&#10084;</span> By
              <span class="highlight-text">Deven Rathod</span>
            </p>
            <div class="footer-img">
              <img
                src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"
                alt="Netlify"
                onClick="location.href='https://www.netlify.com/'"
          
              />

              <img
                src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D"
                alt="Vue.JS"
                onClick="location.href='https://vuejs.org/'"
              />
              <div class="gitcode">
                Get Source Code on Github
              </div>
              <img
                src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"
                alt="Github"
                onClick="location.href='https://github.com/DevenRathod2/landing-page-on-vue.js'"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "DevenRathod",
  props: {
    msg: String,
  },
};
</script>
