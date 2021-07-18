---
title: CSS Questions
layout: layouts/page.njk
permalink: /questions/css-questions/index.html
---

* What is CSS selector specificity and how does it work? - means by which browser decides which styles to apply.
* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why? - combination of both
* Describe Floats and how they work. - one of the methods of layouting. float and clear goes hand in hand.
* Describe z-index and how stacking context is formed. - created by postion relative/absolute/sticky/flex/grid/transform with z-index.
* Describe BFC (Block Formatting Context) and how it works. - solves collapsing margin, wrap around float
* What are the various clearing techniques and which is appropriate for what context? - clear: left/right/both or clearfix class or BFC
* How would you approach fixing browser-specific styling issues? - use autoprefixer plugin, bootstrap, normalize/reset.css
* How do you serve your pages for feature-constrained browsers? - 
  * What techniques/processes do you use? - Graceful degradation,Progressive enhancement, caniuse.com, use autoprefixer plugin
* What are the different ways to visually hide content (and make it available only for screen readers)? - visibility: hidden, heigth/width=0, position outside
* Have you ever used a grid system, and if so, what do you prefer? - i like flex
* Have you used or implemented media queries or mobile specific layouts/CSS? - yes for the entire app
* Are you familiar with styling SVG? - 
* Can you give an example of an `@media` property other than `screen`? - screen, print, speech
* What are some of the "gotchas" for writing efficient CSS? - 
* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used. - dont like additional compile/recompile time
* How would you implement a web design comp that uses non-standard fonts? - use @font-face
* Explain how a browser determines what elements match a CSS selector. - from right to left of selector
* Describe pseudo-elements and discuss what they are used for. - for decoration or adding elements without changing DOM
* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models. - box-sizing: content-box/border-box
* What does ```* { box-sizing: border-box; }``` do? What are its advantages?
* What is the CSS `display` property and can you give a few examples of its use?
* What's the difference between inline and inline-block?
* What's the difference between the "nth-of-type()" and "nth-child()" selectors?
* What's the difference between a relative, fixed, absolute and statically positioned element?
* What existing CSS frameworks have you used locally, or in production? How would you change/improve them? - bootstrap
* Have you used CSS Grid?
* Can you explain the difference between coding a web site to be responsive versus using a mobile-first strategy?
* Have you ever worked with retina graphics? If so, when and what techniques did you use?
* Is there any reason you'd want to use `translate()` instead of *absolute positioning*, or vice-versa? And why? - translate doesn't cause refow & repaint
* How is clearfix css property useful?
* Can you explain the difference between px, em and rem as they relate to font sizing?
* Can you give an example of a pseudo class? Can you provide an example use case for a pseudo class? 
* What is the difference between a block level element and an inline element. Can you provide examples of each type of element?
