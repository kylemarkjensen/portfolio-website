---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  @media (max-width: 57.8125em) {
    /* 1. Center & contain the main sidebar block */
    .sidebar {
      display: flex !important;
      flex-direction: column !important;
      align-items: center !important;
      justify-content: center !important;
      text-align: center !important;
      width: 100% !important;
      max-width: 100% !important;
      margin: 0 auto 30px auto !important;
    }

    /* 2. Flatten table components causing name & image misalignment */
    .sidebar .author__avatar,
    .sidebar .author__content {
      display: block !important;
      width: 100% !important;
      padding: 0 !important;
      margin: 0 auto !important;
      text-align: center !important;
    }

    /* 3. Center and size the avatar container perfectly */
    .sidebar .author__avatar {
      margin-bottom: 15px !important;
    }
    
    .sidebar .author__avatar img {
      max-width: 160px !important;
      width: 160px !important;
      height: 160px !important;
      margin: 0 auto !important;
      display: inline-block !important; /* Prevents block-level layout drift */
    }

    /* 4. Fix name, pronoun, and bio text alignment */
    .sidebar .author__content .author__name,
    .sidebar .author__content .author__bio {
      width: 100% !important;
      text-align: center !important;
      margin-left: auto !important;
      margin-right: auto !important;
    }

    /* 5. FIX THE FOLLOW BUTTON: Prevent unconditional expansion */
    .sidebar .author__urls-wrapper {
      display: block !important;
      width: 100% !important;
      text-align: center !important;
      margin-top: 15px !important;
    }

    /* Restore button layout so it responds to clicks natively */
    .sidebar .author__urls-wrapper button {
      display: inline-block !important; /* Keeps the toggle button visible */
      margin: 0 auto !important;
    }

    /* Fix layout behavior of the hidden/revealed items menu */
    .sidebar .author__urls {
      display: none; /* Let JavaScript control the toggle natively */
      text-align: left !important; /* Keeps structural text neat inside */
      margin: 10px auto 0 auto !important;
      width: max-content !important;
    }

    /* When the theme toggles the 'open' class via JS, display it nicely */
    .sidebar .author__urls-wrapper.open .author__urls {
      display: block !important;
    }
  }
</style>

I’m an experimental psychologist and clinical neuroimaging enthusiast with 10+ years of experience in academic research, teaching, and mentoring students.

I collect, curate, and utilize brain imaging data, applying advanced analytic approaches and developing neuroinformatics tools for establishing brain-based biomarkers of neurological and psychiatric illness. I am passionate about teaching and mentoring and making neuroscience accessible to everyone - through open access initiatives, responsible and organized data management, and by clearly communicating and disseminating key research findings.

I love to learn and I love to share my discoveries. I am passionate about teaching and mentoring and I do all I can to help others succeed. 

### Data-Driven Psychology

I love to explore. I believe that it’s important to expand our range of vision and be open to new ideas and information we may not expect; great discoveries and scientific advancement often result from unexpected sources. I try to search for truth through a wide variety of modalities and methods, although much of my work can be categorized as data-driven.

### Research Interests
I love to study <span id="typed-element" style="color: #52adc8; font-weight: bold;"></span>
{% raw %}
<script src="https://unpkg.com/typed.js@3.0.0/dist/typed.umd.js"></script>
<script>
  function initializeTyped() {
    var typed = new Typed('#typed-element', {
      strings: [
        'biology.', 
        'the human brain.', 
        'mental illness.', 
        'gestalt psychology.', 
        'cognitive neuroscience.', 
        'neuroimaging.', 
        'neuroinformatics.', 
        'functional networks.', 
        'perception.',
        'emotion.',
        'human development.',
        'genetics.'
      ],
      typeSpeed: 50,
      backSpeed: 30,
      backDelay: 1500,
      loop: true
    });
  }

  document.addEventListener('DOMContentLoaded', initializeTyped);
</script>
{% endraw %}
