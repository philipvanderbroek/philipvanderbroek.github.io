---
layout: project-page
title: Transformer
permalink: transformer/
---
# Transformer

### Overview
A common problem in data analysis is that the data is messy.  Cleaning messy data is difficult and often requires technical skills.  Trifacta enables analysts to clean and prepare their data by providing them with a visual cleaning experience powered by machine learning.

The process of cleaning data in Trifacta had been tailored to data scientists, closely resembling a scripting language, making the cleaning process unnecessarily hard for analysts.

Over a year and half we completely redesigned the core experience, replacing the technical scripting interaction model with an assistive and visual interaction model based on workflows, interfaces, and concepts tailored to analysts.

### Problem
<figure><video src="/video/trifacta_old.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>


There were many problems stemming from the scripting interaction model:

- The language was difficult for analysts to understand because it was too technical and Trifacta-specific.
- Learning the language was hard because there wasn’t any documentation or help in context.
- Common functionality was difficult fo find, such as using a formula, because it was nested under obscure commands.
- The page layout was overloaded.
- Visual design and basic interface components needed updating (covered in the [Design System case study](/design_system)).

### Goals
Given the problems, the main goals of the project were to:
- Rethink the transformation crafting and editing experience for analysts by moving away from a scripting interaction model
- Improve discoverability and learnability of commands
- Redesign page layout and interactions to facilitate a better workflow

### Approach
Explore

<figure><img src="/images/transformer/test.png"></figure>

<figure><img src="/images/transformer/test.png"></figure>

Layout
<figure><img src="/images/transformer/test.png"></figure>
<figure><img src="/images/transformer/test.png"></figure>
<figure><img src="/images/transformer/test.png"></figure>

### Final Design
<figure><video src="/video/panel.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>

The final design was a completely new experience for data analysts.

The Builder simplified the complex tasks of cleaning by allowing users to start where they feel comfortable, whether it be browsing options or crafting a specific cleaning command, assisting them during the process of creation by providing help in context. The panel proved to be a robust layout solution, creating a unified, focused experience.

The flexibility and assistance of the Builder broke the confines of the rigid scripting language and catered to the user’s mental model rather than forcing them into an experience oriented around the technical system.

### Impact
Something

<p class="next">
  <a href="/design_system">Next Case Study - Design System
  <?xml version="1.0" ?><svg enable-background="new 0 0 32 32" height="15px" class="arrow" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path clip-rule="evenodd" d="M31.106,15H3.278l8.325-8.293  c0.391-0.391,0.391-1.024,0-1.414c-0.391-0.391-1.024-0.391-1.414,0l-9.9,9.899c-0.385,0.385-0.385,1.029,0,1.414l9.9,9.9  c0.391,0.391,1.024,0.391,1.414,0c0.391-0.391,0.391-1.024,0-1.414L3.278,17h27.828c0.552,0,1-0.448,1-1  C32.106,15.448,31.658,15,31.106,15z" fill="#444444" fill-rule="evenodd" id="Arrow_Back"/><g/><g/><g/><g/><g/><g/></svg>
  </a>
</p>
