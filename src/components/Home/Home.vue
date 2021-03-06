<style src="./home.css"></style>
<template>
  <div id="app">
    <div class="main">
      <div class="container">
        <div class="profile">
          <img src="/profile.jpg" alt="" />
        </div>
        <div class="title">
          <h1 class="title-name">Deven Rathod</h1>
          <p>
            Full Stack Developer <br />
            <span class="highlight-text">@DeveloperSpot</span>
          </p>
        </div>
        <div class="social-container">
          <div class="github">
            <img src="" alt="" />
            <h3 class="social-title">I'm On Github</h3>
          </div>
          <div class="twitter">
            <img src="" alt="" />
            <h3 class="social-title">Also On Twitter</h3>
          </div>
          <div class="linkedin">
            <img src="" alt="" />
            <h3 class="social-title">Lets Connect Here</h3>
          </div>
          <div class="instagram">
            <img src="" alt="" />
            <h3 class="social-title">Follow me Instagram</h3>
          </div>
          <div class="footer-text">
            <p>Design with <span class="highlight-text-red">&#10084;</span> By <span class="highlight-text">Deven Rathod</span></p>
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
