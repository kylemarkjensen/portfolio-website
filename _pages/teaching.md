---
title: "Teaching"
permalink: /teaching/
author_profile: true
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
  /* Safe fallback default: Everything is perfectly visible by default so content ALWAYS loads */
  .scroll-group {
    opacity: 1;
    transform: none;
  }

  /* Modern Scroll-Driven Animations: Executes only if natively supported by the user browser browser */
  @supports (animation-timeline: view()) {
    @keyframes dynamicSlideInLeft {
      0% {
        opacity: 0;
        transform: translateX(-40px); /* Sweeps in from the left frame */
      }
      75% {
        opacity: 1;
        transform: translateX(0);     /* Snaps into place mid-scroll */
      }
      100% {
        opacity: 1;
        transform: translateX(0);
      }
    }

    @keyframes dynamicSlideInRight {
      0% {
        opacity: 0;
        transform: translateX(60px);  /* Sweeps in from the right frame */
      }
      40% {
        opacity: 1;
        transform: translateX(0);
      }
      100% {
        opacity: 1;
        transform: translateX(0);
      }
    }

    /* Apply viewport-aware scroll tracking properties natively */
    .scroll-group {
      animation-timeline: view();
      animation-range: entry 5% cover 40%; /* Triggers as elements rise from screen bottom */
      animation-fill-mode: both;
    }

    .reveal-left {
      animation-name: dynamicSlideInLeft;
    }

    .reveal-right {
      animation-name: dynamicSlideInRight;
    }
  }
  
  /* Base styles for large screens (Desktop) */
  .responsive-flex-container {
    display: flex;
    flex-flow: row wrap; /* Side-by-side by default */
    gap: 16px;
    width: 100%;
    align-items: stretch; /* Forces wrappers to be equal height */
    margin: 25px 0;
  }

  .text-wrapper {
    flex: 1;
    min-width: 300px; /* Triggers the wrap when space gets tight */
    display: block;
  }

  /* Enhanced styling to make the introduction paragraph pop */
  .intro-text {
    font-size: 1.18rem;       /* Marginally larger for better presence */
    font-weight: 450;         /* Slightly bolder than normal text for emphasis */
    font-style: italic;       /* Elegant italic flow */
    color: #2d3748;           /* Darker charcoal slate for sharper legibility */
    line-height: 1.65;
    margin: 0 !important;             
    padding: 18px 20px;       /* Generous internal spacing inside the background panel */
    background-color: #f7fafc;/* Soft, neutral off-white/light gray panel tint */
    border-left: 4px solid #3182ce; /* Distinct, professional accent color bar on the left edge */
    border-radius: 4px 14px 14px 4px; /* Matches your image border radius smoothly */
  }

  .image-wrapper {
    flex: 1;
    min-width: 300px;
    position: relative;       /* Allows the child image to anchor to this wrapper's height */
    min-height: 100%;
  }

  .image-wrapper img {
    position: absolute;       /* Frees image from structural sizing, forcing it to look at the wrapper */
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;        /* Crops image cleanly to match text height perfectly */
  }

  /* Responsive styles for small screens (Mobile phones) */
  @media (max-width: 768px) {
    .responsive-flex-container {
      /* Reverses row order and stacks them so the image comes first */
      flex-flow: column-reverse nowrap; 
    }

    .text-wrapper {
      display: block;         /* Reverts to standard block flow on mobile */
    }
    .image-wrapper {
      min-height: 250px;     /* Gives it a fixed structure on mobile */
    }
    
    .image-wrapper img {
      position: relative;     /* Restores normal layout flowing for mobile screens */
      height: 250px;
    }
  }
</style>

<!-- Responsive Flexbox Container: Columns stack on mobile, side-by-side on desktop -->
<div class="responsive-flex-container">
  
  <!-- Left Text Wrapper -->
  <div class="text-wrapper scroll-group reveal-left" markdown="1">
 <p class="intro-text">Teaching is an integral part of who I am as a person; to explain why I teach is more of a biography than a statement of purpose. As an educator, I recognize that I am endowed with great responsibility. Part of this responsibility includes describing and elaborating on the methods of how I teach.</p>
  </div>
  
  <!-- Right Image Wrapper -->
  <div class="image-wrapper scroll-group reveal-right">
    <img src="/images/Brain_Puzzle_cropped.jpg" alt="brain puzzle image">
  </div>

</div>

<!-- Content Group 1: Lifelong Learner -->
<div class="scroll-group reveal-left" markdown="1">
<h3>I am a lifelong learner.</h3>
</div>
<div class="scroll-group reveal-left" markdown="1">
While knowledge and experience are attributes inherently required of my position and role, I do not consider myself to be some kind of all-knowing sage. Rather, I am an individual informed by relevant first-hand experience, who is adequately prepared to share with fellow students a unique perspective on knowledge which my field has deemed accurate, valuable, and useful. I am an ally who is prepared to share with students my own secrets to success. I am prepared to train students to develop the same skills which I have developed, or to help them identify desirable knowledge or skills which I may not possess and then direct them to sources where they can get the help that they need.
</div>

<!-- Content Group 2: Bridge -->
<div class="scroll-group reveal-left" markdown="1">
<h3>I am a bridge.</h3>
</div>
<div class="scroll-group reveal-left" markdown="1">
I must help bridge the gap between my students and future employers, whether those employers are in industry or academia. This role highlights my duty to know what employers expect from their employees so that I can accurately represent and communicate the expectations of possible employers to students in a way that is accessible to them through clear course and learning objectives. I also have a duty to help students to meet those expectations by structuring the course to provide opportunities to gain the knowledge they need and develop the skills which will be required of them. This is done through preparation for and participation in class. Then, I must accurately evaluate how well a student achieves those objectives so that their performance and progress can be communicated back to those employers in the form of grades and recommendations.
</div>

<div class="scroll-group reveal-left" markdown="1">
I also serve as a bridge between a student and new ideas. I hope to help students expand their minds as they consider new perspectives and possibilities. I do not wish to mold them into any one way of thinking, but rather to help them learn to be agents for themselves by more fully realizing their own autonomy in light of new knowledge. What does this look like in the classroom? Students will be given more than one way to solve a problem, answer a question, or complete an assessment. Specifically, in my lectures, I try to avoid phrasing questions with only one specific answer in mind. For example, rather than asking students to regurgitate a textbook definition of the psychological construct of personality, I could ask them, “What does personality mean to you?” or “How would you describe your best friend’s personality?” followed up by asking them to make connections to what the field of psychology teaches about personality. I strive to encourage and reward unique perspectives from students who think outside the box. This technique for asking open ended questions and rewarding thoughtful responses extends to my quizzes and exams in the form of short answer questions graded with specification rubrics. While there are certain things which students must know and demonstrate, I believe that there can be flexibility in how they do it.
</div>

<!-- Content Group 3: Advocate -->
<div class="scroll-group reveal-left" markdown="1">
<h3>I am an advocate.</h3>
</div>
<div class="scroll-group reveal-left" markdown="1">
I advocate on behalf of employers and institutions to my students, and I advocate on behalf of my students to employers and institutions. My courses can be simplified into 3 parts: Preparation, participation, and demonstration. Preparation and participation are the tools I primarily use to advocate for employers and institutions. Through preparatory readings, short lectures, in-class activities emphasizing active learning and group interaction, and various forms of formative assessment, I help students learn the things employers and institutions expect them to know and develop the skills they are expected to have.
</div>

<div class="scroll-group reveal-left" markdown="1">
I do not give busy work or use lectures, activities, assignments, or assessments simply as filler for a course. My time is precious, and my students’ time is precious. For this reason, all forms of formative and summative assessment appropriately align with and thoroughly accomplish course and learning objectives. It is my greatest hope that students will care about the topics and skills which compose my courses and I hope that they will find each part of the course to be relevant, meaningful, and enjoyable.
</div>

<div class="scroll-group reveal-left" markdown="1">
Demonstration is a tool I use to advocate for my students. Demonstration is a method for following up on a student’s preparation and participation. It is an assessment of how well students have achieved course and learning objectives and it is clearly related to specific objectives. Transparency with students ensures that there will be no surprises – unless of course the objective of an assessment requires the student to adapt innovative solutions to an unexpected challenge. By producing deliverables in the form of projects and summative assessment, students can demonstrate in a tangible, observable, and objective way the great things that they will bring to the table if they are hired or funded. Top marks in my class will distinguish a student and be meaningful to the student and to employers as they reflect engagement and effort more than innate ability or aptitude. Top marks will be a realistic and achievable goal for every student as I strive to realize the potential in everyone.
</div>
