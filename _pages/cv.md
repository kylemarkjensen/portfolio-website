---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

<!-- Embedded styles managing anchor layout, hover animations, focus ring removal, and iframe modal pop-ups -->
<style>
  .cv-item-card {
    display: flex;
    text-decoration: none !important; /* Removes default link underlines */
    color: inherit !important;        /* Keeps original text colors intact */
    transition: all 0.25s ease-in-out; /* Smooth transition for desktop hover */
    border-radius: 6px;
    padding: 10px;                     
    
    /* Crucial for iOS/Safari: tells the browser to recognize custom tap behavior */
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0); 
  }

  /* 🛠️ REMOVE ORANGE CLICK BOX (Focus Ring Outlines) */
  .cv-item-card:focus,
  .cv-item-card:focus-visible,
  .cv-item-card:active {
    outline: none !important;
    box-shadow: none !important; /* Overrides template-level shadow flashes on press */
  }

  /* 💻 Desktop/Mouse Hover Effect */
  @media (hover: hover) {
    .cv-item-card:hover {
      background-color: rgba(0, 0, 0, 0.03); /* Subtle backdrop tint */
      transform: translateY(-2px);           /* Lifts the card slightly up */
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08); /* Soft drop shadow expansion */
    }
    .cv-item-card:hover .cv-card-location i {
      color: #4a90e2; 
    }
  }

  /* 📱 Smartphone/Touch Active Feedback State */
  .cv-item-card:active {
    background-color: rgba(0, 0, 0, 0.06) !important; /* Deeper tint for concrete touch confirmation */
    transform: scale(0.99);                            /* Slight compression effect under the thumb */
    transition: all 0.05s ease;                        /* Instantaneous response speed */
  }

  /* 🔳 IFRAME MODAL STYLES */
  .cv-modal-overlay {
    display: none; 
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6); /* Dimmed backdrop overlay */
    z-index: 2000;
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(2px);
  }

  .cv-modal-window {
    background: #ffffff;
    padding: 0; /* Let iframe expand across the entire surface area */
    border-radius: 8px;
    width: 90%;
    max-width: 850px; /* Expansive presentation space for nested pages */
    height: 85%; /* Scaled vertically for text tracking layouts */
    position: relative;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.25);
    overflow: hidden; /* Clips iframe inner frames elegantly */
    animation: fadeInModal 0.2s ease-out;
  }

  .cv-modal-close-btn {
    position: absolute;
    top: 15px;
    right: 20px;
    background: #ffffff;
    border: 1px solid #ddd;
    border-radius: 50%;
    width: 36px;
    height: 36px;
    font-size: 24px;
    cursor: pointer;
    color: #333;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    z-index: 2010;
  }
  
  .cv-modal-close-btn:hover {
    background: #f5f5f5;
    color: #000;
  }

  .cv-modal-body {
    width: 100%;
    height: 100%;
  }

  .cv-modal-iframe {
    width: 100%;
    height: 100%;
    border: none;
    background: #ffffff;
  }

  @keyframes fadeInModal {
    from { opacity: 0; transform: scale(0.97); }
    to { opacity: 1; transform: scale(1); }
  }
</style>

<div class="cv-grid-layout">
  
  <div class="cv-sub-nav vertical-right">
    <a href="#education" class="cv-nav-link">Education</a>
    <a href="#experience" class="cv-nav-link">Experience</a>
    <a href="#awards" class="cv-nav-link">Awards</a>
    <a href="#service" class="cv-nav-link">Service</a>
  </div>
  
  <div class="cv-stream-content">

    <div class="cv-section" id="education">
      <h2>Education</h2>
      <div class="cv-block-container">
        <a href="/cv/phd/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2021 - 05/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Ph.D. in Psychology</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details">Cognitive and Affective Neuroscience</div>
          </div>
        </a>
        <a href="/cv/ma/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2019 - 08/2021</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Las Cruces, NM</div>
          </div>
          <div class="cv-card-content">
            <h4>M.A. in Psychology</h4>
            <div class="cv-institution">New Mexico State University</div>
            <div class="cv-details">Cognitive Psychology</div>
          </div>
        </a>
        <a href="/cv/bs/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">09/2012 - 07/2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>B.S. in Psychology</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details">Health Psychology</div>
          </div>
        </a>
      </div>
    </div>

    <div class="cv-section" id="experience">
      <h2>Experience</h2>
      <div class="cv-block-container">
        <a href="/cv/experience/data_manager/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">06/2026 - Present</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Data Administrator Lead</h4>
            <div class="cv-institution">TReNDS Center</div>
          </div>
        </a>
        <a href="/cv/experience/GRA/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2021 - 05/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Graduate Research Assistant</h4>
            <div class="cv-institution">Georgia State University</div>
          </div>
        </a>
        <a href="/cv/experience/admin_assist/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2020 - 06/2021</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Las Cruces, NM</div>
          </div>
          <div class="cv-card-content">
            <h4>Administrative Assistant</h4>
            <div class="cv-institution">New Mexico State University</div>
          </div>
        </a>
        <a href="/cv/experience/GTA/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2019 - 05/2021</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Las Cruces, NM</div>
          </div>
          <div class="cv-card-content">
            <h4>Graduate Teaching Assistant</h4>
            <div class="cv-institution">New Mexico State University</div>
          </div>
        </a>
        <a href="/cv/experience/adjunct/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">09/2017 - 12/2018</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Adjunct Instructor</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
          </div>
        </a>
        <a href="/cv/experience/dm_byui/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">01/2018 - 06/2018</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Data Manager</h4>
            <div class="cv-institution">Alere Youth Development</div>
          </div>
        </a>
        <a href="/cv/experience/undergrad_TA/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">09/2016 - 07/2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Undergraduate Teaching Assistant</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
          </div>
        </a>
      </div>
    </div>
    
    <div class="cv-section" id="awards">
      <h2>Awards</h2>
      <div class="cv-block-container">
        <a href="/cv/awards/trends_poster/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">05/2025</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Research Excellence Poster Award</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/ignite/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">03/2025</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Ignite Doctoral Research Achievement Award</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/trends_scholar/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">12/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Distinguished Scholarship Award</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/CABI/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">09/2023</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Competitive Trainee Scholarship</h4>
            <div class="cv-institution">GSU/GA Tech Center for Advanced Brain Imaging (CABI)</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/2CI/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">07/2021 - 07/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>2CI Neurogenomics Doctoral Fellowship</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/outstanding_GA/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2020 - 2021</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Las Cruces, NM</div>
          </div>
          <div class="cv-card-content">
            <h4>Outstanding Graduate Assistantship Award</h4>
            <div class="cv-institution">New Mexico State University</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/FDSMR/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">05/2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Faculty Development & Student Mentored Research Award</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/travel/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">04/2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Student Travel Award</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/byui_excellence/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2016 - 2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Academic Excellence Scholarship</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/eagle/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">07/2012</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Beaverton, OR</div>
          </div>
          <div class="cv-card-content">
            <h4>Eagle Scout</h4>
            <div class="cv-institution">Boy Scouts of America (BSA)</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/awards/health_careers/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">06/2012</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Beaverton, OR</div>
          </div>
          <div class="cv-card-content">
            <h4>Health Careers Program Graduate</h4>
            <div class="cv-institution">Beaverton High School</div>
            <div class="cv-details"></div>
          </div>
        </a>
      </div>
    </div>

    <div class="cv-section" id="service">
      <h2>Service</h2>
      <div class="cv-block-container">
        <a href="/cv/service/mentoring/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2026 - Present</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Co-Mentor</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details">University Assistantship Program</div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">08/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Poster Judge</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Summer 2026 TReNDS Research Day</div>
          </div>
        </a>
        <a href="/cv/service/mentoring/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">05/2026 - 08/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Mentor</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details">CASA & D-MAP</div>
          </div>
        </a>
        <a href="/cv/service/mentoring/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">04/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Invited Panelist</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Spring 2026 TReNDS Research Day</div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">04/2026</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Poster Judge</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Spring 2026 TReNDS Research Day</div>
          </div>
        </a>
        <a href="/cv/service/mentoring/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">12/2025</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Invited Panelist</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Fall 2025 TReNDS Research Day</div>
          </div>
        </a>
        <a href="/cv/service/ATL_science_festival/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">03/2025</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Volunteer/Exhibitor</h4>
            <div class="cv-institution">Atlanta Science Festival</div>
            <div class="cv-details">Neuroscience Booth</div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">12/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Poster Judge</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Fall 2024 TReNDS Research Day</div>
          </div>
        </a>
        <a href="/cv/service/CABI_EEG/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Volunteer</h4>
            <div class="cv-institution">GSU/GA Tech Center for Advanced Brain Imaging</div>
            <div class="cv-details">Media Development</div>
          </div>
        </a>
        <a href="/cv/service/AD_walk/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">11/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Participant</h4>
            <div class="cv-institution">Walk to End Alzheimer's</div>
            <div class="cv-details">TReNDS Center</div>
          </div>
        </a>
        <a href="/cv/service/CABI_EEG/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">10/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Station Leader</h4>
            <div class="cv-institution">TReNDS Center</div>
            <div class="cv-details">Brain Blast: A Brain Health Exploration</div>
          </div>
        </a>
        <a href="/cv/service/CABI_EEG/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">02/2024 & 04/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Volunteer</h4>
            <div class="cv-institution">GSU/GA Tech CABI</div>
            <div class="cv-details">Student Field Trip EEG Demos</div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Reviewer</h4>
            <div class="cv-institution">Journal of International Medical Research</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/service/ATL_science_festival/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">03/2024</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Volunteer/Exhibitor</h4>
            <div class="cv-institution">Atlanta Science Festival</div>
            <div class="cv-details">Neuroscience Booth</div>
            <div class="cv-details">CABI EEG Demo</div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2023</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Reviewer</h4>
            <div class="cv-institution">Schizophrenia Bulletin</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/service/reviewer/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2022</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Atlanta, GA</div>
          </div>
          <div class="cv-card-content">
            <h4>Reviewer</h4>
            <div class="cv-institution">Georgia State University</div>
            <div class="cv-details">Aging Research Conference</div>
          </div>
        </a>
        <a href="/cv/service/webmaster/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2020 - 2021</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Las Cruces, NM</div>
          </div>
          <div class="cv-card-content">
            <h4>Webmaster</h4>
            <div class="cv-institution">NMSU Psychology Equity, Diversity, & Inclusion Committee</div>
            <div class="cv-details"></div>
          </div>
        </a>
        <a href="/cv/service/pos_psych_lab/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2017 - 2019</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Lab Manager</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details">Positive Psychology Lab</div>
          </div>
        </a>
        <a href="/cv/service/pos_psych_lab/" class="cv-item-card">
          <div class="cv-card-left-column">
            <div class="cv-card-date">2016 - 2017</div>
            <div class="cv-card-location"><i class="fas fa-map-marker-alt"></i> Rexburg, ID</div>
          </div>
          <div class="cv-card-content">
            <h4>Undergraduate RA</h4>
            <div class="cv-institution">Brigham Young University - Idaho</div>
            <div class="cv-details">Positive Psychology Lab</div>
          </div>
        </a>
      </div>
    </div>

  </div>
</div>

<!-- Reusable Pop-Up Window Structure with an iFrame -->
<div id="cvModalOverlay" class="cv-modal-overlay">
  <div class="cv-modal-window">
    <button id="cvModalClose" class="cv-modal-close-btn">&times;</button>
    <div id="cvModalBody" class="cv-modal-body">
      <!-- The iframe will be created and injected here dynamically via JavaScript -->
    </div>
  </div>
</div>

<script type="text/javascript">
  function runScrollspy() {
    var sections = document.querySelectorAll('.cv-section');
    var navLinks = document.querySelectorAll('.cv-nav-link');
    if (!sections.length || !navLinks.length) return;
    window.addEventListener('scroll', function() {
      var currentSectionId = "";
      var scrollPosition = window.scrollY || window.pageYOffset;
      var triggerPoint = scrollPosition + 140;
      sections.forEach(function(section) {
        var sectionTop = section.offsetTop;
        var sectionHeight = section.offsetHeight;
        if (triggerPoint >= sectionTop && triggerPoint < (sectionTop + sectionHeight)) {
          currentSectionId = section.getAttribute('id');
        }
      });
      if (!currentSectionId && sections.length) {
        currentSectionId = sections[0].getAttribute('id');
      }
      navLinks.forEach(function(link) {
        var targetHref = link.getAttribute('href');
        if (targetHref === '#' + currentSectionId) {
          link.classList.add('active');
        } else {
          link.classList.remove('active');
        }
      });
    });
  }
  
  function runModalSetup() {
    var modalOverlay = document.getElementById('cvModalOverlay');
    var modalBody = document.getElementById('cvModalBody');
    var closeModalBtn = document.getElementById('cvModalClose');
    var cards = document.querySelectorAll('.cv-item-card');

    if (!modalOverlay || !modalBody || !closeModalBtn || !cards.length) return;

    // Monitor clicks on all item cards
    cards.forEach(function(card) {
      card.addEventListener('click', function(e) {
        // Get the page destination already listed on the card
        var targetUrl = this.getAttribute('href');
        
        // Safety skip: Only turn it into a popup if it's pointing to a legitimate sub-page
        if (targetUrl && targetUrl !== '#' && !targetUrl.startsWith('#')) {
          e.preventDefault(); // Stop native top-level browser redirect
          
          // Dynamically create the iframe and point it to your existing sub-page
          modalBody.innerHTML = '<iframe src="' + targetUrl + '" class="cv-modal-iframe"></iframe>';
          
          modalOverlay.style.display = 'flex';             // Reveal overlay
          document.body.style.overflow = 'hidden';         // Lock background body scroll
        }
      });
    });

    // Close modal routine
    function closeModal() {
      modalOverlay.style.display = 'none';
      modalBody.innerHTML = '';          // Wipe iframe context to free up memory
      document.body.style.overflow = ''; // Restore background body scroll
    }

    closeModalBtn.addEventListener('click', closeModal);
    
    // Close if user clicks directly on the dim backdrop overlay border
    modalOverlay.addEventListener('click', function(e) {
      if (e.target === modalOverlay) closeModal();
    });
  }

  window.addEventListener('DOMContentLoaded', function() {
    runScrollspy();
    runModalSetup();
  });
  window.addEventListener('load', function() {
    runScrollspy();
    runModalSetup();
  });
</script>
