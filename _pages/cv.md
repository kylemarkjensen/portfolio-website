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

<!-- SECTION 1: EDUCATION -->
    <div class="cv-section" id="education">
      <h2>Education</h2>

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
</div>

<!-- SECTION 2: EXPERIENCE -->
<div class="cv-section" id="experience">
      <h2>Experience</h2>

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
</div>

<!-- SECTION 3: Awards -->
<div class="cv-section" id="awards">
      <h2>Awards</h2>

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
</div>

<!-- SECTION 4: Service -->
<div class="cv-section" id="service">
      <h2>Service</h2>

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
</div>

<!-- Robust Scrollspy Script for academicpages -->
<script>
  window.addEventListener('load', () => {
    // 1. Target headings and navigation links
    const sections = document.querySelectorAll('h2[id]');
    const navLinks = document.querySelectorAll('.cv-nav-link');

    if (!sections.length || !navLinks.length) return;

    // 2. Optimized Observer Config for deep layout containers
    const observerOptions = {
      root: null, 
      // Expand the window tracking grid: checks a broad horizontal slice near top-middle
      rootMargin: '-5% 0px -55% 0px', 
      threshold: [0, 0.1, 0.2]
    };

    // Keep track of which sections are currently crossing into the view block
    const visibleSections = new Map();

    const observer = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        // Map true/false visibility tracking markers
        visibleSections.set(entry.target.getAttribute('id'), entry.isIntersecting);
      });

      // Find the first section that is actively intersecting the viewport banner
      let activeId = null;
      for (const [id, isIntersecting] of visibleSections.entries()) {
        if (isIntersecting) {
          activeId = id;
          break; // Grab the highest up visible element block
        }
      }

      // 3. Fallback: If scrolling fast and nothing matches, find the closest header above the fold
      if (!activeId) {
        let closestSection = null;
        let closestDistance = -Infinity;

        sections.forEach(section => {
          const rect = section.getBoundingClientRect();
          // If the heading is above the middle of screen, it's a potential current read match
          if (rect.top <= window.innerHeight / 2 && rect.top > closestDistance) {
            closestDistance = rect.top;
            closestSection = section;
          }
        });
        if (closestSection) activeId = closestSection.getAttribute('id');
      }

      // 4. Force inject class updating states
      if (activeId) {
        navLinks.forEach(link => {
          const href = link.getAttribute('href');
          if (href === `#${activeId}`) {
            link.classList.add('active');
          } else {
            link.classList.remove('active');
          }
        });
      }
    }, observerOptions);

    // 5. Fire observer tracking routine
    sections.forEach(section => observer.observe(section));
  });
</script>
