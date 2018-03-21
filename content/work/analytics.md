---
title: Metaps Analytics
description: Dashboard UX + landing page
author: Philip John Madeley
date: 2015-03-01
publishDate: 2015-03-01
# categories: [category 1, category 2]
# tags: [tag 1, tag 2]
comments: false
generatePage: false
img_thumbnail: "images/tm_an@2x.jpg"
class: an
draft: false
---

![Hero image](/images/an_top_sm@2x.jpg)

## Overview
Metaps is an app monetization platform focused on how to maximize revenue and optimize campaign performance. This was an on-going project over about 16 months which was split into two parts:

1. Design and implement modular components for the preexisting dashboard
2. Redesign the landing page

In this case study, I will only discuss the dashboard funnel and segment analytics tools.

## Ideation
Kickoff meetings were held with a product manager to figure out the goals, scope, and constraints of each project.  These meetings were conducted around a whiteboard, followed up with a round of discussion and, more importantly, a comprehension check of each other's ideas.

After that, I used mind mapping to uncover and explore possible solutions.  For research, benchmarking the competition and testing out current solutions in the market helped solve some key decisions regarding the user journey.  In the example,  I created user flows for a funnel to track dropoff and conversion rates.  

![Ideation user flow](/images/an_ideation_userflow.jpg)

## Iteration
To achieve quick results, I used Keynote and then, later on, InVision to prototype wireframes into a clickable user experience.  Allowing the team to play through the experience and leave comments proved invaluable to quickly iterate on designs.  In the example, I use rapid wireframing to test a user flow for saving out a segment.

<div class="responsive-container">
<iframe src="https://player.vimeo.com/video/161468167?title=0&byline=0&portrait=0" width="900" height="607" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

Once the user flows and UI had been signed off, I used Sketch to create high fidelity mocks and surface any concerns about integration with the existing UI style guide. This process was repeated for other modular dashboard components.

## Implementation
The initial stage leveraged the Foundation framework and Rails asset pipeline to build out static views. Once the layout and sizing were pixel perfect, the focus turned to integrating the motion and how each action would link to the next task. Although the user flows were tested in the  prototype, implementing animations and responders in the UI with jQuery were important for user experience.

<div class="responsive-container">
<iframe src="https://player.vimeo.com/video/161471190?title=0&byline=0&portrait=0" width="900" height="499" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div>

## Retrospective
Although this product was in its initial stages of development, having more user data prior to the ideation phase would have solved some early decision making.

![Landing page on mobile](/images/an_mobile.jpg)


## Visit
The landing page was rebranded under www.metaps.com as of June 2015. The dashboard can only be accessed with a user account.
