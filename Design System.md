---
layout: project-page
title: Design System
permalink: design_system/
hero: "/images/design_system/design_system_hero.png"
---
# Design System

### Overview

After 3 years of building features with loose design guidelines, Trifacta’s product was showing its rough edges.  The interface had visual and interactive design issues as well as a poorly architected front end.  Both design and engineering were burdened by a lack of consistent components.  It was time to tackle the problem with a proper design system.

The design system initiative was kicked off by myself and the principal designer on my team. The principal designer led the execution and I supported him with planning, coordination, and by creating time and visisbility.

Educating the company was essential because many people didn't understand what a design system was and why we should work on it compared to other features. We started with an analysis of the problem and a proposed approach.  We presented them to the company to help everyone understand the goals.

The initiative gained momentum and became a formal joint effort between Front End and Design.  We ultimately shipped completely redone components and layouts to the product and a design system in sketch and code.

### Problem

We were familiar with problem through our day to day work, but we began to formalize it by auditing Trifacta’s UI.  The UI was full of inconsistencies, causing pain for us as designers, our developers, and our users.  Simple components like lists and menus had many, many variations.

<figure><img src="/images/design_system/bag_o_components.png"></figure>

In addition to inconsistencies, the UI was lacking a strong visual design perspective.  The interface had become a generic use of many blues and grays.  We dubbed the problem “50 shades of gray”.

<figure><img src="/images/design_system/shades.png"></figure>

### Approach
After understanding the scope the problem, we began mapping existing components to new standardized components.  We also considered primitive properties such as type and padding.

<figure><img src="/images/design_system/standard_menus.png"></figure>

<figure><img src="/images/design_system/type.png"></figure>

The principal designer created a prototype in code to test the design system as it evolved.  This also allowed us to easily share our progress with developers and the broader company; all they had to do was ping a url.

In our weekly design team meeting we would discuss progress and assign out particular tasks.  We would also use that time to discuss real instances of the components in features we were working on to understand the considerations in a true context. The principal designer and I had weekly meetings and ad hoc collaboration with the front end developers throughout the process.

### Final Result

The final result was a detailed and documented set of components in sketch and code, and significant updates to product itself.

<figure><img src="/images/design_system/type2.png"></figure>
<figure><img src="/images/design_system/colors.png"></figure>
<figure><img src="/images/design_system/layout.png"></figure>
<figure><img src="/images/design_system/buttons.png"></figure>
<figure><img src="/images/design_system/transformer.png"></figure>
<figure><img src="/images/design_system/flow.png"></figure>

### Design tools and workflow

We implemented the system in sketch using a shared symbols library.   With the shared symbols library we could be more productive at creating high fidelity mockups.  It also acted as a standardizing force: if you aren’t using a shared symbol, why not?

We uploaded a shared master sketch file to google drive and would create a new file from it whenever we started a new project.  There are of course some challenges with that workflow, but it was dead simple and just worked for us.

<figure><video src="/video/dspreview.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>

### Challenges

The design system initiative was challenging to resource.  The work didn’t easily fit into our release schedule since it was ongoing and we and the developers would frequently have to trade off design system effort against high priority feature work or customer escalations.  By working with Engineering, I helped create a formal design system team with a dedicated dev leader and resource, which made a difference.

### Impact

Despite the challenges, the design system had a large impact the product and the way we worked as Product and Engineering groups.

Upon leaving Trifacta, the CEO mentioned he thought the Design System was one of my biggest contributions to the company and was impressed I carved out the team’s time to focus on the initiative against competing priorities.

<figure><img src="/images/design_system/before_after.png"></figure>

<p class="next">
  <a href="/management">Next Case Study - Design Management
    <?xml version="1.0" ?><svg enable-background="new 0 0 32 32" height="15px" class="arrow" version="1.1" viewBox="0 0 32 32" width="32px" xml:space="preserve" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><path clip-rule="evenodd" d="M31.106,15H3.278l8.325-8.293  c0.391-0.391,0.391-1.024,0-1.414c-0.391-0.391-1.024-0.391-1.414,0l-9.9,9.899c-0.385,0.385-0.385,1.029,0,1.414l9.9,9.9  c0.391,0.391,1.024,0.391,1.414,0c0.391-0.391,0.391-1.024,0-1.414L3.278,17h27.828c0.552,0,1-0.448,1-1  C32.106,15.448,31.658,15,31.106,15z" fill="#444444" fill-rule="evenodd" id="Arrow_Back"/><g/><g/><g/><g/><g/><g/></svg>
  </a>
</p>
