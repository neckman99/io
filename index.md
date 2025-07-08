---
layout: page
---

<style>
.split-container {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 20px;
}

.split-left {
  flex: 0 0 60%; /* Left side takes 60% width */
  min-width: 300px;
}

.split-left img {
  width: 100%;  /* Make image fill the container width */
  height: auto;
  border-radius: 8px;
  object-fit: cover;
}

.split-right {
  flex: 0 0 40%; /* Right side takes 40% width */
  min-width: 200px;
  font-size: 1.1rem;
  line-height: 1.5;
}
</style>


<div class="split-container">
  <div class="split-left">
    <img src="/assets/headshot.jpg" alt="NJE" />
  </div>
  <div class="split-right">
    <h2>about me</h2>
    I'm a researcher and chemical engineer interested in the future of drug delivery, polymers, and digital biology. Poke around here to have a look at my CV, projects, and more.
  </div>
</div>
