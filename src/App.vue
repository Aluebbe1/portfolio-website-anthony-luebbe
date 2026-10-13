<template>
  <div id="app">
    <!-- Navigation Bar -->
    <header class="navbar">
      <div class="container">
        <div class="logo">Anthony Luebbe</div>
        <nav>
          <ul class="nav-links">
            <li><a href="#" class="active">Home</a></li>
            <li><a href="#focus">Career Focus</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <!-- Hero / Intro Section -->
    <main class="hero">
      <div class="container hero-grid">
        <div class="profile-card">
          <img 
            src="/headshot.png" 
            alt="Anthony Luebbe" 
            class="profile-img"
          />
        </div>
        <div class="hero-content">
          <h1>Anthony Luebbe</h1>
          <p class="subtitle">Future Systems & Software Developer</p>
          <div class="bio-text">
            <p>
              Welcome to my portfolio! I am currently pursuing an Associate of Applied Science in Information Technology & Systems Development at Central Community College.
            </p>
            <p>
              With extensive practical experience in operations, quality control, and technical problem-solving, I bring a detail-oriented, pragmatic approach to modern web application development and system logic.
            </p>
          </div>
        </div>
      </div>
    </main>

    <!-- Career Focus Section -->
    <section id="focus" class="focus-section">
      <div class="container">
        <h2>Future Developer Focus</h2>
        <div class="focus-grid">
          <div class="card">
            <h3>Frontend Web Development</h3>
            <p>Creating dynamic, accessible interfaces using Vue 3, Vite, JavaScript, HTML5, and modern CSS layout techniques.</p>
          </div>
          <div class="card">
            <h3>Backend & Database Systems</h3>
            <p>Developing structured server logic and relational data stores using Python, Java, C#, Flask, and SQL Server.</p>
          </div>
          <div class="card">
            <h3>Version Control & Cloud Deployment</h3>
            <p>Maintaining clean codebase management and continuous deployment workflows with Git, GitHub, and Netlify.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <div class="container">
        <p>&copy; 2026 Anthony Luebbe | Personal Portfolio</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
</script>
