---
layout: essay
type: essay
title: "Why don't U and I Frame these Works"
# All dates must be YYYY-MM-DD format!
date: 2025-10-08
published: true
labels:
  - Bootsrap 5
  - Essay
  - UI Frameworks
---

## How does one do this?

Moore was correct; this was indeed one of the most harrowing and tedious units. I was familiar with HTML but very new to Bootstrap 5 before this module. I know it’s redundant to say it was like learning a new language, but it really was. There were classes, spacing, typography, and other components I still have yet to get used to. But why bother using Bootstrap 5 at all? Why did I spend so much time trying to move an icon or anything to the left or right? To play devil’s advocate, I’d say that most people who bother anyway are those frameworks that repay that learning cost with speed, consistency, and fewer bugs. With raw HTML and CSS, you have complete control and flexibility over every aspect of design and functionality, allowing for highly customized and unique interfaces. For example, decisions between flex and grid layouts, custom breakpoints, browser quirks, and accessibility details that you must remember each time. With Bootstrap 5, the framework gives you production-ready components like the responsive grid, navbar, and utility classes, meaning you can focus on product logic instead of reinventing layouts for the fifth time.

Bootstrap 5’s grid is an excellent example of this. When writing container > row > col-12 col-md-4, it creates a mobile-first layout that reshapes itself at breakpoints without custom media queries. The same is true for ‘d-flex, justify-content-between, gap-*, and gx-*,’ which turns the spacing and alignment to a readable intent. Readability is essential for groups, as everyone can understand the change even without looking at a stylesheet, when someone says, "make it col-md-6 and add gx-5." Plus, Bootstrap includes a lot of cross-browser and accessibility functionality. Although it's not a free pass, components include functional roles, keyboard behavior, and focus styles; they're a better starting point than the majority of quick custom builds. Meaning that you don't need to set up JavaScript in most cases—data attributes and the included JS handle the majority of it—and your forms, navbars, and more will work as expected across devices.
	Bootstrap 5 is excellent for most, but I do have my qualms with it. HTML with CSS was already a harrowing experience, but now I have to create all these navbars, footers, links, etc. Making a basic navbar transition from links to a hamburger icon took a significant amount of time to prevent it from jumping or overlapping the logo. Centering hero text over a full-width image in my head was going to be easy, but on my overheating laptop, the image stretched, the text shifted at different screen sizes, or the overlay became too dark/light. Even a “simple” three-column footer was tedious. Columns were too tight on the desktop, forms were not aligning with the text, and icons were disappearing because I forgot a class name or for some other reason. On top of that, there's so much to choose from. How significant should the gaps be? What do I name these classes so they don’t collide later? What should I quit?


<center>
  <img width="600px" src="/img/code-framework-line-icon-vector.jpg
">
</center>

## I'm tired of this grandpa  

Though this module might be my mortal enemy, a wise man once said, “Keep your friends close and your enemies closer.” However, by using the practice WODs and online resources, I feel like I’ve gotten a handle on it, more like a pinch, but it’s the touch that counts. For layouts, always begin with container → row → col-*, then scale with ‘col-”, “md”, “lg-”, and adjust space with gx-* or gy-*. For navbars, keep everything that should collapse within a single element. Collapse with an id, pair it with one navbar-toggler, and let navbar-expand-lg determine when it becomes a hamburger. Center the text with position-absolute top-50 start-50 translate-middle. Most "just nudge it a little" tasks were replaced with utility tweaks (mt-3, ps-lg-5, text-center, d-flex align-items-center) rather than new CSS. That shift did stop being annoying, but it did reduce it to predictable, copy-and-pasteable patterns.
  
All in all, Bootstrap 5 is an excellent tool as it speeds up the process, is consistent, and has fewer surprises; in return, you receive massive headaches, a hot laptop, and maybe a misaligned icon or text. Don’t forget Raw HTML and CSS! It’s great for when the page is small or extremely customizable–but for anything with a navbar, hero, footer, and navigation menus. Although it may take years off my life, frameworks are essential for teams and companies, as they enable consistent and fast collaboration with peers, and I see myself using them in the near future.


