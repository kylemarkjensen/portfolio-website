---
title: "Ph.D. in Psychology"
excerpt: "With background image"
collection: portfolio
permalink: /cv/phd/
header:
  teaser: "assets/img/12.jpg"
sidebar:
  - title: "Role"
    image: "assets/img/12.jpg"
    text: "Brief project overview or metadata here."
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

<a href="/cv/" class="btn btn--info" style="margin-bottom: 20px; display: inline-flex; align-items: center; gap: 8px; text-decoration: none !important;">
  <i class="fas fa-arrow-left"></i> Back to CV
</a>

***

### Full-Width Feature

![Main Feature Image](/images/cv/mentors.jpg)
*This image can also have a caption below it. It's like magic.*

***

You can also put regular text between your rows of images. For inline academic citations, `academicpages` utilizes standard Markdown footnotes or a global bibliography instead of theme-specific Liquid syntax. 

Say you wanted to write a bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next layout framework.

### Split Layout (2/3 and 1/3 Content Showcase)

For asymmetrical photo arrangements, use direct HTML image elements aligned natively within the `academicpages` content framework:

<div style="display: flex; gap: 15px; flex-wrap: wrap;">
  <div style="flex: 2; min-width: 250px;">
    <img src="/images/cv/grad.JPG" alt="example image 2/3 width" style="border-radius: 4px; box-shadow: 0 1px 1px rgba(0,0,0,0.125);">
  </div>
  <div style="flex: 1; min-width: 150px;">
    <img src="/images/cv/grad_family.jpeg" alt="example image 1/3 width" style="border-radius: 4px; box-shadow: 0 1px 1px rgba(0,0,0,0.125);">
  </div>
</div>

<!-- Flexbox Layout Container for Perfectly Equal Height Images -->
<div style="display: flex; gap: 16px; width: 100%; align-items: stretch; margin: 25px 0;">
  
  <!-- Left Image Wrapper -->
  <div style="flex: 1; display: flex;">
    <img src="/images/cv/grad.JPG" alt="Left project image" style="width: 100%; height: 100%; object-fit: cover;">
  </div>
  
  <!-- Right Image Wrapper -->
  <div style="flex: 1; display: flex;">
    <img src="/images/cv/grad_family.jpeg" alt="Right project image" style="width: 100%; height: 100%; object-fit: cover;">
  </div>

</div>

*You can also have artistically styled 2/3 + 1/3 images, like these.*

The Markdown structure is simple. Keep formatting clean so that the responsive styles native to the template handle mobile layout scaling flawlessly.

