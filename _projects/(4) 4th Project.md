---
name: Portfolio Project
tools: [html, css]
image: https://screenshot.codepen.io/3193076.GaELbp.bafbe3de-68fe-4409-81e7-a2d727d84e08.png
description: A minimalist portfolio design
---

## Portfolio Page

A Portfolio page sampling the work of a fictional character. In this page navigation is used so that it is easier to stay within the page. Pictures and links in a compact layout put the artist front and center. This a project in the Free Code Camp curriculum for HTML/CSS and Responsive Design.

[Link to Portfolio in CodePen]https://codepen.io/lmldvd/pen/GaELbp

{% capture carousel_images %}
images/fcc-portfolio-1.png
images/fcc-portfolio-2.png
images/fcc-portfolio-3.png
{% endcapture %}

{% include elements/carousel.html %}
