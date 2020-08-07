<template>
  <div id="nav_bar">
    <a class="logo">
      <img src="@/assets/logoBOnP.png" alt="F logo" style="width:20px;height:30px;" />
      <img
        src="@/assets/logo_sub.png"
        alt="FDP | FrontEnd Developer"
        style="width:30px;height:auto;"
      />
    </a>
    <nav class="en">
      <a href="#" rel="index" class="home-link">
        <i class="fas fa-home icon-home"></i>
        <span>HOME</span>
      </a>
      <a href="#" rel="about" class="about-link">
        <i class="fas fa-user-alt"></i>
        <span>ABOUT</span>
      </a>
      <a href="#" rel="skills" class="skills-link">
        <i class="fas fa-cog"></i>
        <span>SKILLS</span>
      </a>
      <a href="#" rel="my-work" class="my-work-link">
        <i class="far fa-eye"></i>
        <span>WORKS</span>
      </a>
      <a href="#" rel="contact" class="contact-link">
        <i class="far fa-envelope"></i>
        <span>CONTACT</span>
      </a>
    </nav>
    <ul>
      <li>
        <a href="https://twitter.com/fabio_dp1" target="_blank">
          <i class="fab fa-twitter social-icon"></i>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/fabio-di-pane-39971222/" target="_blank">
          <i class="fab fa-linkedin-in social-icon"></i>
        </a>
      </li>
      <li>
        <a href="https://www.facebook.com/dipane.fabio/" target="_blank">
          <i class="fab fa-facebook-f social-icon"></i>
        </a>
      </li>
      <li>
        <a href="https://github.com/fabiodp1" target="_blank">
          <i class="fab fa-github-alt social-icon"></i>
        </a>
      </li>
    </ul>
  </div>
</template>

<style scoped>
#nav_bar {
  background: #181818;
  width: 60px;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  z-index: 3;
  min-height: 500px;
}

#nav_bar nav {
  display: block;
  text-align: center;
}
#nav_bar nav a {
  font-size: 20px;
  color: #909096;
  margin-bottom: 15px;
  display: block;
  line-height: 51px;
  height: 51px;
  position: relative;
  text-decoration: none;
}

.logo img {
  display: block;
  margin: 8px auto;
  width: 24px;
  height: auto;
}
#nav_bar nav a i {
  transition: opacity 0.3s ease-in;
  opacity: 1;
  height: auto;
}

#nav_bar nav a:hover i {
  opacity: 0;
  height: 0;
  overflow: hidden;
}
#nav_bar nav a span {
  opacity: 0;
  height: 0;
  overflow: hidden;
}
#nav_bar nav a:hover span {
  transition: opacity 0.3s ease-in;
  display: block;
  color: #fc0893;
  font-size: 9px;
  letter-spacing: 2px;
  position: absolute;
  bottom: 0;
  width: 100%;
  text-align: center;
  opacity: 1;
  height: auto;
}

#nav_bar ul {
  display: block;
  padding: 0;
  list-style: none;
  text-align: center;
  margin: 0;
  padding-bottom: 20px;
}

#nav_bar ul li a {
  padding: 7px 0;
  display: block;
  font-size: 15px;
  line-height: 16px;
  color: #909096;
}

#nav_bar ul li a:hover {
  transition: color 0.3s ease-in;
  color: #fc0893;
}
</style>
