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
  .cv-floating-back-btn {
    position: fixed;
    top: 20px;
    left: 20px;
    z-index: 999;
    padding: 10px 16px;
    background-color: #ffffff;
    color: #333333 !important;
    border: 1px solid #e1e4e8;
    border-radius: 20px;
    font-size: 14px;
    font-weight: 500;
    text-decoration: none !important;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: all 0.2s ease-in-out;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }
  .cv-floating-back-btn:hover {
    background-color: #f6f8fa;
    transform: translateX(-2px);
    box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  }
  /* Hides it if it overlaps your sidebar profile on larger desktop layouts */
  @media (max-width: 1024px) {
    .cv-floating-back-btn {
      position: relative;
      top: 0;
      left: 0;
      margin-bottom: 20px;
      display: inline-flex;
    }
  }
</style>

<a href="/cv/" class="cv-floating-back-btn">
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

*You can also have artistically styled 2/3 + 1/3 images, like these.*

The Markdown structure is simple. Keep formatting clean so that the responsive styles native to the template handle mobile layout scaling flawlessly.

