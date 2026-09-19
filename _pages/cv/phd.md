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

Every project has a beautiful feature showcase page. 
It's easy to include images in a flexible multi-column layout or format your photos in various widths.

To give your project a background or teaser image in the portfolio collection page, just add the `teaser` tag under `header` in the front matter like so:

```yaml
---
title: "Project Title"
collection: portfolio
header:
  teaser: "assets/img/12.jpg"
---
```

### Gallery Showcase

Below is a three-column representation of the project photos.

| ![Road through a tunnel](/assets/img/1.jpg) | ![Artistic leaves fall](/assets/img/3.jpg) | ![Lumberjack grasping needles](/assets/img/5.jpg) |
|:---:|:---:|:---:|
| A road goes through a tunnel. | Leaves artistically fall in a photoshoot. | A lumberjack grasps pine needles. |

***

### Full-Width Feature

![Main Feature Image](/assets/img/5.jpg)
*This image can also have a caption below it. It's like magic.*

***

You can also put regular text between your rows of images. For inline academic citations, `academicpages` utilizes standard Markdown footnotes or a global bibliography instead of theme-specific Liquid syntax. 

Say you wanted to write a bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next layout framework.

### Split Layout (2/3 and 1/3 Content Showcase)

For asymmetrical photo arrangements, use direct HTML image elements aligned natively within the `academicpages` content framework:

<div style="display: flex; gap: 15px; flex-wrap: wrap;">
  <div style="flex: 2; min-width: 250px;">
    <img src="/assets/img/6.jpg" alt="example image 2/3 width" style="border-radius: 4px; box-shadow: 0 1px 1px rgba(0,0,0,0.125);">
  </div>
  <div style="flex: 1; min-width: 150px;">
    <img src="/assets/img/11.jpg" alt="example image 1/3 width" style="border-radius: 4px; box-shadow: 0 1px 1px rgba(0,0,0,0.125);">
  </div>
</div>

*You can also have artistically styled 2/3 + 1/3 images, like these.*

The Markdown structure is simple. Keep formatting clean so that the responsive styles native to the template handle mobile layout scaling flawlessly.

