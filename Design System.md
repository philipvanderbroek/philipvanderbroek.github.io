---
layout: project-page
title: Design System
permalink: design_system/
---
# Design System

### Overview

After 3 years of building features with loose design guidelines, Trifacta’s product was showing its rough edges.  The interface had visual and interactive design issues as well as a poorly architected front end.  Both design and engineering were burdened by a lack of consistent components.  It was time to tackle the problem with a proper design system.

The design system initiative was kicked off by myself and the principal designer on my team and the principal designer led the effort.  Educating the company was essential. We started with an analysis and proposal to help the organization understand what the problems were and what we felt like a good approach would look like.

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

The principal designer implemented a prototyping branch in code to test the design system as it evolved.  This also allowed us to easily share our progress with developers and the broader company.

In our weekly design team meeting we would discuss progress and assign out particular tasks.  We would also use that time to discuss real instances of the components in features we were working on to understand the considerations in a real context. The principal designer and I had weekly meetings and ad hoc collaboration with the front end developers throughout the process.


### Final Result

The final result was a detailed and documented set of components in sketch and code, and significant updates to product itself.

Image Here

Design tool and workflow

The design system was captured in sketch leveraging a shared symbols library.   With the shared symbols library we could be more productive at creating high fidelity mockups.  It also acted as a standardizing force.  If you aren’t using a shared symbol, why not?

We uploaded a shared master sketch file to google drive and would create a new file from that whenever we started a new project.  There are of course some challenges with that workflow, but it was dead simple and just worked for us.

<figure><video src="/video/dspreview.mov" autobuffer="" loop="" muted="" autoplay="" preload="auto"></video></figure>

### Challenges

The design system initiative was challenging to resource.  As a project it didn’t easily fit into our release schedule since it was ongoing and we and the developers would frequently have to trade off design system effort against high priority feature work or customer escalations.  Some attempts to time box effort with a “Design System Week” helped, but were ultimately insufficient.  Further efforts were made to integrate design system work into feature work.  Again, this helped but was insufficient.   By working with the VP of Engineering, I helped create a formal design system team with a dedicated dev leader and resource, which made a difference.

Collaborating with development was also a challenge.  The front end team didn’t initially have a formal leader - they were all peers - which led to challenges with ownership and accountability.  These were contributing factors to the creation of the formal design system team.

### Impact

Before and After Image

Despite the challenges, the design system had a large impact the product and the way we worked as Product and Engineering organization.

Upon leaving Trifacta, the CEO mentioned he thought the Design System was one of my biggest contributions to the company and was impressed I carved out the team’s time to focus on the initiative against competing priorities.


<p class="next">
  <a href="/management">Next Case Study - Design Management</a>
</p>
