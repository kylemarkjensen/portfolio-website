---
title: "Atlanta Science Festival"
excerpt: "With background image"
collection: portfolio
permalink: /cv/service/ATL_science_festival/
---

<style>
  /* Target all images within the primary content body */
  .page__content img {
    border: 1px solid #e1e4e8 !important; /* Crisp, neutral light-grey border frame */
    border-radius: 14px !important;        /* Smooth, modern rounded corners */
    padding: 5px;                          /* Creates a clean, professional passport-photo border effect */
    background-color: #ffffff;             /* Ensures a clean white gap between the image and the frame border */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.06); /* Very subtle bottom drop shadow for depth */
    transition: transform 0.2s ease-in-out;
  }
</style>

<style>
  /* Base styles for large screens (Desktop) */
  .responsive-flex-container {
    display: flex;
    flex-flow: row wrap; /* Side-by-side by default */
    gap: 16px;
    width: 100%;
    align-items: stretch;
    margin: 25px 0;
  }

  .text-wrapper {
    flex: 1;
    min-width: 300px; /* Triggers the wrap when space gets tight */
    display: block;
  }

  .image-wrapper {
    flex: 1;
    min-width: 300px;
    display: flex;
  }

  .image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  /* Responsive styles for small screens (Mobile phones) */
  @media (max-width: 768px) {
    .responsive-flex-container {
      /* Reverses row order and stacks them so the image comes first */
      flex-flow: column-reverse nowrap; 
    }
    
    .image-wrapper img {
      height: 250px; /* Prevents the image from becoming stretched or giant on mobile */
    }
  }
</style>

<!-- Responsive Flexbox Container: Columns stack on mobile, side-by-side on desktop -->
<div class="responsive-flex-container">
  
  <!-- Left Text Wrapper (Will wrap below the image on small screens) -->
  <div class="text-wrapper" markdown="1">
 During my Ph.D. at GSU, I had several opportunities to attend and volunteer in the famous Atlanta Science Festival. I love science outreach events that I can bring my family to! I've highlighted my involvement as a volunteer/exhibitor below:

*Volunteer/Exhibitor: GSU/GA Tech/Emory Neuroscience Booth at the Exploration Expo at Piedmont Park (March 22, 2025)*

*Volunteer/Exhibitor: GSU/GA Tech/Emory Neuroscience Booth at the Exploration Expo at Piedmont Park (March 23, 2024)*

*EEG Demo at GSU/GA Tech Center for Advanced Brain Imaging (also see <a href="/cv/service/CABI_EEG/">CABI EEG</a>; March 9, 2024)*
  </div>
  
  <!-- Right Image Wrapper (Will wrap to the top on small screens) -->
  <div class="image-wrapper">
    <img src="/images/cv/ATL_science_festival.jpeg" alt="Right project image" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

</div>

<iframe src="https://atlantasciencefestival.org/" width="100%" height="500px" style="border:none;">
  <p>Your browser does not support iframes.</p>
</iframe>

<style>
  /* LIGHT MODE STYLE (Default state) */
  .custom-back-btn {
    margin-bottom: 25px;
    display: inline-flex;
    align-items: center;
    gap: 8px;
    text-decoration: none !important;
    padding: 6px 14px;
    border-radius: 6px;
    font-size: 0.9rem;
    font-weight: 500;
    
    background-color: transparent !important;
    color: #495057 !important;           /* Dark slate text */
    border: 1px solid #ced4da !important;   /* Subtle border frame */
    transition: all 0.25s ease-in-out !important;
  }

  /* Hover state for Light Mode */
  .custom-back-btn:hover {
    background-color: #f8f9fa !important;
    color: #17a2b8 !important;            /* Accent cyan */
    border-color: #17a2b8 !important;
    transform: translateX(-2px); 
  }

  /* UNIVERSAL DARK MODE SELECTOR (Triggers directly off your manual toggle) */
  html.dark .custom-back-btn,
  body.dark .custom-back-btn,
  html.dark-theme .custom-back-btn,
  body.dark-theme .custom-back-btn,
  html.dark-mode .custom-back-btn,
  body.dark-mode .custom-back-btn,
  [data-theme="dark"] .custom-back-btn {
    color: #f8f9fa !important;            /* High-contrast bright text prior to hover */
    border-color: #495057 !important;     /* Mid-tone visible frame border */
    background-color: rgba(255, 255, 255, 0.08) !important; /* Low light surface visibility background */
  }
  
  /* Hover state when Dark Mode toggle is engaged */
  html.dark .custom-back-btn:hover,
  body.dark .custom-back-btn:hover,
  html.dark-theme .custom-back-btn:hover,
  body.dark-theme .custom-back-btn:hover,
  html.dark-mode .custom-back-btn:hover,
  body.dark-mode .custom-back-btn:hover,
  [data-theme="dark"] .custom-back-btn:hover {
    background-color: rgba(100, 210, 255, 0.15) !important; 
    color: #64d2ff !important;            /* Vibrant light neon-blue */
    border-color: #64d2ff !important;
  }
</style>

<a href="/cv/" class="custom-back-btn">
  <i class="fas fa-arrow-left" style="font-size: 0.8rem;"></i> Back to CV
</a>
