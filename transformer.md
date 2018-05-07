---
layout: project-page
title: Transform Builder
permalink: transformer/
hero: "/images/transformer/transformer_project_hero.png"
---
# Transform Builder

### Overview
A common problem in data analysis is that the data is messy. Cleaning messy data is difficult and often requires technical skills that data analysts don't have.  Trifacta enables analysts to clean and prepare their data by providing them with a visual cleaning experience powered by machine learning.

The process of cleaning data in Trifacta had previously been tailored to data scientists, closely resembling a scripting language, making the cleaning process unnecessarily hard for analysts.

Over the span of a year and half we completely redesigned the core cleaning experience, replacing the technical scripting interaction model with an assistive and visual interface interaction model based on workflows and concepts tailored to analysts.

### Problem
<figure><video src="/video/trifacta_old.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>

There were many problems with the scripting interaction model:

- The language was difficult for analysts to understand because it was too technical and Trifacta specific.
- Learning the language was hard because there wasn’t any documentation or help in context.
- Common commands were difficult fo find, such as using a formula, because they were nested under obscure commands.
- The page layout was overloaded.
- Visual design and basic interface components needed updating (covered in the [Design System case study](/design_system)).

### Goals
Given the problems, the goals of the project were to:
- Rethink the transformation crafting and editing experience for analysts.
- Improve discoverability and learnability of commands.
- Redesign page layout and interactions to facilitate a better workflow.

### Approach
Because scripting was difficult for our users we knew we wanted to move to a visual interface-based model.  The details of such a model weren't clear, so we explored breaking the scripting language out into atomic components.  In this way we could design simple experiences for each type of command.

<figure><img src="/images/transformer/types.png"></figure>

We explored putting the atomic components in the bottom panel.

<figure><img src="/images/transformer/bottom_panel.png"></figure>


The script input needed a lot of horizontal space, but after moving towards an interface based solution, we realized we could break free from the bottom panel.  With the bottom panel, the page layout was overloaded because there was both a bottom scripting panel and a contextual right panel.  The multiple panels made the page feel cluttered and the workflow feel inconsistent.  Also, the bottom panel wouldn't easily scale to more complex commands that took up more horizontal space.

We wanted to simplify the layout and workflow by unifying the bottom panel with the right panel. Taking inspiration from apps such as keynote, we explored a panel layout.

<figure><img src="/images/transformer/panel_concept.png"></figure>

The panel approach was really promising, so we dug into the details.  We wanted to understand the workflow in more detail, such as what searching and crafting in a panel would entail.  We also wanted to explore how the unified panel might contain and the atomic components we had explored before.

<figure><img src="/images/transformer/single_panel.png"></figure>

The panel was both robust as a page layout and flexible in the types of workflows and components it could contain.

### Final Design
<figure><video src="/video/panel.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>

The final design was a completely new experience for data analysts.  The main improvements were:

 - **Better search and discovery paths** so users can find the transform they’re looking for.
 - **More support and documentation** integrated into the app so users can learn and understand the features.
 - **A better panel layout** creating a unified, focused experience and workflow.

The flexibility and assistance of the Builder broke the confines of the rigid scripting language by **catering to how analysts think about crafting cleaning steps** rather than forcing them into an experience oriented around the technical system.

<p class="next">
  <a href="/design_system">Next Case Study - Design System
  <?xml version="1.0" ?><svg enable-background="new 0 0 32 32" height="15px" class="arrow" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path clip-rule="evenodd" d="M31.106,15H3.278l8.325-8.293  c0.391-0.391,0.391-1.024,0-1.414c-0.391-0.391-1.024-0.391-1.414,0l-9.9,9.899c-0.385,0.385-0.385,1.029,0,1.414l9.9,9.9  c0.391,0.391,1.024,0.391,1.414,0c0.391-0.391,0.391-1.024,0-1.414L3.278,17h27.828c0.552,0,1-0.448,1-1  C32.106,15.448,31.658,15,31.106,15z" fill="#444444" fill-rule="evenodd" id="Arrow_Back"/><g/><g/><g/><g/><g/><g/></svg>
  </a>
</p>
