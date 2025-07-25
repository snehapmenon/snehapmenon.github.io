---
layout: default
title: "Welcome"
---

<style>
  body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
  }

  header {
    background-color: #000;
    color: #fff;
    padding: 1em 2em;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  nav a {
    color: #fff;
    margin-left: 1em;
    text-decoration: none;
    font-weight: bold;
  }

  .content {
    display: flex;
    flex-direction: row;
    padding: 2em;
    max-width: 1000px;
    margin: auto;
    gap: 2em;
  }

  .photo {
    flex: 1;
  }

  .photo img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
  }

  .bio {
    flex: 2;
  }

  @media (max-width: 768px) {
    .content {
      flex-direction: column;
    }
  }
</style>

<header>
  <div><strong>My Academic Site</strong></div>
  <nav>
    <a href="/">About</a>
    <a href="/research.html">Research</a>
    <a href="/policy.html">Policy</a>
  </nav>
</header>

<div class="content">
  <div class="photo">
    <img src="/assets/img/profile.png" alt="Profile Photo">
  </div>
  <div class="bio">
  <h1>Welcome</h1>
  <p>Hello! I’m [Your Name], a researcher at [Your Institution]. My work explores [your focus area].</p>
  <p>Use the navigation bar to explore my work on research and policy.</p>
  </div>
</div>
