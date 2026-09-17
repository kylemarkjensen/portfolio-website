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

</div> <!-- Explicitly closes cv-block container -->
</div> <!-- Explicitly closes education -->

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

</div> <!-- Explicitly closes cv-block container -->
</div> <!-- Explicitly closes experience -->

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

</div> <!-- Explicitly closes cv-block container -->
</div> <!-- Explicitly closes awards -->

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

</div> <!-- Explicitly closes cv-block container -->
</div> <!-- Explicitly closes service -->

</div> <!-- Explicitly closes cv-stream-content -->
</div> <!-- Explicitly closes cv-grid-layout -->

<script>
  function runScrollspy() {
    const sections = document.querySelectorAll('.cv-section');
    const navLinks = document.querySelectorAll('.cv-nav-link');
    
    if (!sections.length || !navLinks.length) return;

    // Track user position down the page loop
    window.addEventListener('scroll', () => {
      let currentSectionId = "";
      
      // Calculate exactly where the top view line cuts across your content
      const scrollPosition = window.scrollY || window.pageYOffset;
      const triggerPoint = scrollPosition + 120; // safe top margin buffer

      sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.offsetHeight;

        // Check if the current scroll position rests inside this section box boundary
        if (triggerPoint >= sectionTop && triggerPoint < (sectionTop + sectionHeight)) {
          currentSectionId = section.getAttribute('id');
        }
      });

      // If we scrolled past the bottom or haven't hit a box, fallback to the first element
      if (!currentSectionId && sections.length) {
        currentSectionId = sections[0].getAttribute('id');
      }

      // Inject the active status class name mapping directly
      navLinks.forEach(link => {
        const targetHref = link.getAttribute('href');
        if (targetHref === `#${currentSectionId}`) {
          link.classList.add('active');
        } else {
          link.classList.remove('active');
        }
      });
    });
  }

  // Double down on execution timing parameters
  window.addEventListener('DOMContentLoaded', runScrollspy);
  window.addEventListener('load', runScrollspy);
</script>
