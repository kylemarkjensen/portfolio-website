---
layout: archive
title: "CV (Under Construction)"
permalink: /cv/
author_profile: true
---
<!-- main right-nav grid wrapper container -->
<div class="cv-grid-layout">
  
<!-- Right-Side Vertical Sticky Bar -->
  <div class="cv-sub-nav vertical-right">
    <a href="#education" class="cv-nav-link">Education</a>
    <a href="#experience" class="cv-nav-link">Experience</a>
    <a href="#awards" class="cv-nav-link">Awards</a>
    <a href="#service" class="cv-nav-link">Service</a>
  </div>
  
<!-- Main CV Stream Content Column -->
  <div class="cv-stream-content">

<h2 id="education">Education</h2>

<div class="cv-block-container">

  <!-- Card 1 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">08/2021 - 05/2026</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Atlanta, GA </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>Ph.D. in Psychology</h4>
      <div class="cv-institution">Georgia State University</div>
      <div class="cv-details">
        Cognitive and Affective Neuroscience
      </div>
    </div>
  </div>
  
  <!-- Card 2 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">08/2019 - 08/2021</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Las Cruces, NM </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>M.A. in Psychology</h4>
      <div class="cv-institution">New Mexico State University</div>
      <div class="cv-details">
        Cognitive Psychology
      </div>
    </div>
  </div>

  <!-- Card 3 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">09/2012 - 07/2017</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Rexburg, ID </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>B.S. in Psychology</h4>
      <div class="cv-institution">Brigham Young University - Idaho</div>
      <div class="cv-details">
        Health Psychology
      </div>
    </div>
  </div>

</div>

<h2 id="experience">Experience</h2>

<div class="cv-block-container">

  <!-- Card 1 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">06/2026 - Present</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Atlanta, GA </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>Data Administrator Lead</h4>
      <div class="cv-institution">TReNDS Center</div>
      <div class="cv-details">
        <ul>
          <li>Aligning Research to Impact Autism (ARIA) Initiative</li>
        </ul>
      </div>
    </div>
  </div>

  <!-- Card 2 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">08/2021 - 05/2026</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Atlanta, GA </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>Graduate Research Assistant</h4>
      <div class="cv-institution">Georgia State University</div>
      <div class="cv-details">
        <ul>
          <li>PIs: Drs. Vince D. Calhoun, Armin Iraji, Jessica A. Turner</li>
        </ul>
      </div>
    </div>
  </div>

</div>

<h2 id="awards">Awards</h2>

<div class="cv-block-container">

  <!-- Card 1 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">2025</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Atlanta, GA </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>Ignite Doctoral Research Achievement Award</h4>
      <div class="cv-institution">Georgia State University</div>
      <div class="cv-details">
      </div>
    </div>
  </div>

</div>

<h2 id="service">Service</h2>

<div class="cv-block-container">

  <!-- Card 1 -->
  <div class="cv-item-card">
    <div class="cv-card-left-column">
    <!-- Left Side Column: Holds both Date and Location -->
      <div class="cv-card-date">year</div>
      <div class="cv-card-location">
        <i class="fas fa-map-marker-alt"></i> Location </div>
    </div>
    <!-- Right Side Column: Content -->
    <div class="cv-card-content">
      <h4>Activity</h4>
      <div class="cv-institution">Institution</div>
      <div class="cv-details">
      </div>
    </div>
  </div>

</div>

<!-- Native IntersectionObserver Scrollspy Script -->
<script>
  window.addEventListener('DOMContentLoaded', () => {
    // 1. Grab all h2 section header anchors and side nav links
    const sections = document.querySelectorAll('h2[id]');
    const navLinks = document.querySelectorAll('.cv-nav-link');

    // 2. Set up the observer configuration rules
    const observerOptions = {
      root: null,
      rootMargin: '-10% 0px -70% 0px', // Triggers when the section reaches the upper portion of screen
      threshold: 0
    };

    // 3. Track active elements
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          const id = entry.target.getAttribute('id');
          
          // Clear active states and bind to current anchor
          navLinks.forEach(link => {
            if (link.getAttribute('href') === `#${id}`) {
              link.classList.add('active');
            } else {
              link.classList.remove('active');
            }
          });
        }
      });
    }, observerOptions);

    // 4. Fire observer loop
    sections.forEach(section => observer.observe(section));
  });
</script>
