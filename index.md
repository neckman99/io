---
layout: page
---

<style>
.split-container {
  display: flex;
  flex-direction: column;  /* stack vertically */
  align-items: center;
  gap: 20px;
}

.split-left img {
  width: 100%;
  max-width: 600px;  /* optional max width */
  height: auto;
  border-radius: 8px;
}

.split-right {
  max-width: 600px;  /* keep text aligned nicely */
  font-size: 1.1rem;
  line-height: 1.5;
  text-align: left;
}
</style>

<div class="split-container">
  <div class="split-left">
    <img src="/assets/headshot.jpg" alt="NE" />
  </div>
  <div class="split-right">
    <h2>about me</h2>
    I'm a researcher and chemical engineer interested in the future of drug delivery, polymers, and digital biology. Poke around here to have a look at my [CV]({{ "/bio/" | relative_url }}), [projects]({{ "/papers/" | relative_url }}) and [more]({{ "/nature/" | relative_url }})
  </div>
</div>
