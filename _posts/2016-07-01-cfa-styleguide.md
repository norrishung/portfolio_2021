---
layout: post
title: How we gave products at Code for America a dignified, friendly, and unified style.
category: archived
description: In 2016, another designer and I led an bottom-up effort to create a org-wide styleguide. It has elevated Code for America’s design standards and brought product teams together.
organization: Code for America
role: Design system development
hero: /portfolio/cfa-styleguide/cfa_styleguide_hero.png
---

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_hero.png %}
</figure>

In 2016, another designer and I led an bottom-up effort to create a org-wide styleguide that has elevated Code for America’s design standards and brought product teams together.

## Opportunity

In 2016, Code for America decided to build an in-house product team after primarily depending on a fellowship model. Many of the existing fellowship products and their teams were brought on staff. This presented a few challenges for the organization:

  * Products all had their own design vocabulary.
  * Designers were not used to collaborating.
  * Designers constantly felt like they were reinventing the wheel.
  * Because every product started from scratch, design polish never became a priority.

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_noncohesive.png %}
  <figcaption>
    <p>The state of Code for America products in 2016 before we launched the styleguide.</p>
  </figcaption>
</figure>

After hearing the same challanges across project teams, I, along with fellow designer, decided to do something about it. When we were asked to start a redesign of GetCalFresh, we instead advocated for an extra month to work with the rest of the organization and build something we felt everyone else would want to use as well.


## Research/Planning

We started the project by talking to all of our important stakeholders - other designers, product managers, and company leadership. Some of our research activities included:

  * Taking inventory of all active projects.
  * Facilitating a design values session with designers.
  * Looking at existing user research.
  * Kicking-off the project with org-wide leadership.
  * Committing to working in the open: started a slack channel, blogged about our process, committed to sharing out our progress regularly.

From these meetings, we synthesized a set of design principles that we used to begin our design explorations.

## Design Explorations

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_daniella.jpeg %}
  <figcaption>
    <p>A fellow designer and I being very designer-y during the exploration phase.</p>
  </figcaption>
</figure>

At first, many of our initial explorations were an adaption of Code for America’s existing brand. However, we realized that Code for America’s exist brand was targeted rallying technologies and funders to the cause of civic technology and it did not make sense to use that as the foundation for a design system targeted towards people trying to access the safety net.

We opened ourselves up to use a design language that positioned ourselves authentically to the users of our services.

- We were not a government entity, so we would not pretend to look like one.
- Many of our users may be physically/visually impaired and therefore accessibility must be front and center.
- Because many of our users' primary devices were low-end phones or lived in places without strong reception, perfomance would also be crucial.
- Our users were human-beings that deserved to be treated with dignity. Our designs, imagery, and langauge must reflect that.

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_explorations.png %}
  <figcaption>
    <p>Early visual explorations</p>
  </figcaption>
</figure>

## Implementation

After settling on a design direction that the organization was happy with, I led front-end development of the styleguide using GetCalFresh.org as our first implementation. We used modern front-end conventions such as Atomic Design, Sass, and BEM. I created a living styleguide page that documented all of our patterns for anyone to reference.

As I worked on GetCalFresh wth our new styleguide, user-testing informed many iterative changes over the next year. After a successful implementation on GetCalFresh, other teams began to ask if they could use the styleguide on their projects. We would discuss the ramifications of a refactor and if it was the right time. If we decided the answer was yes, I would help onboard other teams onto using the styleguide.

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_docs.png %}
  <figcaption>
    <p>A living styleguide documenting patterns and code examples.</p>
  </figcaption>
</figure>



The first few projects understood that the process would be painful. However, it was from those pain points that we learned how to adjust the styleguide to be something uniquely shaped for our organization.

## Adoption

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_slack.png %}
  <figcaption>
    <p>Teammates making important decisions about the styleguide :)</p>
  </figcaption>
</figure>

Many people hear “styleguide” and think about the tangible things such as branding, pattern libraries, or stylesheets. The real secret is: a styleguide is all about relationships. Most of the work really looks like this:

- rallying your team and getting them excited about adoption.
- finding the right opportunities to use it on a new project.
- supporting teammates as they transition to your new system.
- see how others use it and address their pain points.
- allowing space for others to contribute while still maintaining a confident editorial voice.

Of course, creating a compelling design that people want to use is important. But making sure you do your research, involve all your stakeholders, and commit to building the relationships over time are all things you need to do to make sure a styleguide sticks.

## Impact

<figure>
  {% picture /portfolio/cfa-styleguide/cfa_styleguide_cohesive.png %}
  <figcaption>
    <p>What Code for America projects look like today. Clockwise from top: ClearMyRecord, ReportChangesColorado, ClientComm, GetCalFresh.</p>
  </figcaption>
</figure>

Three years later, the CfA Styleguide is finally used across all products at Code for America. It is a well-tested system that is accessible, mobile-friendly, performant, and designed specifically for people accessing the safety net.

At this point, many of the strongest contributions are lead by other designs and engineers. A fellow engineer helped to package the styleguide into its own ruby gem and manages contributions from other engineers. Another product designer has helped to develop numerous additional design patterns and created a sketch symbol library. Yet another engineer has been a huge advocate for improving accessibility and WCAG 2.0 Level AA compliance. 

While there will always be more to be done, we are at least now all now working towards a singular goal. Decisions can be made as a team and improvements that benefit one team end up benefiting everyone. 

The best part is that the styleguide is open-source. We encourage anyone working on public-benefit services to use it in their projects.
