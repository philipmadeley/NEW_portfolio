---
title: Smart oven
description: Cooking companion
author: Philip John Madeley
date: 2018-01-15
publishDate: 2018-01-15
# categories: [category 1, category 2]
# tags: [tag 1, tag 2]
comments: false
generatePage: false
img_thumbnail: "images/so_v2.gif"
class: dr_so
draft: false
---

![Hero image](/images/so_v2.gif)

## Overview
The connected home is becoming a reality for more and more people. This project explored a smart oven concept and some of the design implications of such an app.   

## Identifying the target user
Since this was a quick personal project, I harvested secondary research to understand who might benefit most from using a smart oven. Here's a TL;DR of the salient points:

- British women with children feel the most pressure to start chores, including cooking, after returning home from work
- Working British parents between the ages of 16-25 experience the most burnout after work
- The average Brit spends below 5.9 hours a week in the kitchen
- 26% of Brits are passionate about cooking
- 22% of Brits would say they are knowledgeable
- UK Women spend more time cooking than men
- Older age groups with more income tend to spend more on groceries per week
- Saving money is the main reason to cook at home (US)
- 58% of full-time workers cook at home 3-6 times a week  (US)

<div class="framed">
  <img src="/images/so_insights.jpg">
</div>

## User stories
There was an overwhelming amount of secondary research on working mums struggling to cope with work and family life. <i>I have such a hard time trying to scheduling in cooking...</i> was a common quote from the working mums forum
<a class="link" href="https://www.whattoexpect.com/forums/working-moms/topic/how-do-you-do-dinner.html" target="blank">Source</a>

## Insights and assumptions
To focus the design, I narrowed down on who might benefit most from a smart oven.

- Working mums have underserved needs to provide meals after commuting home
- Saving money and eating a healthier diet are the top reasons to cook at home
- Smart home penetration is forecast for 24% in 2018 with adults aged 35-44 making the most frequent online purchases
- Parents with children would eat the same meals together, as opposed to babies under 12 months
- Smart home adoption drops off for people aged 45 and over
- Food preparation is required but can be a user pain-point of knowing how to create variance, and plan accordingly.

## User needs statement
Sonia is a full-time office worker who recently returned to work after her second child. She needs a way to cook meals when she's not able to be in the kitchen.  She has a hard time scheduling time to cook and wants to spend more time with her family. Her goal is to provide healthy, home-cooked meals throughout the week.

![Hero image](/images/so_user-needs.jpg)

## Hypothesis
From my research, I’ve listed 3 main product design goals. The main use case is to start and finish the cooking process when no-one is present.

**On time**
It’s crucial that dinner is cooked and ready for a specific time; children (and some adults) can become irritated when hungry. The design needs to prioritise a user's time when interacting with the product. Design affordances need to be clear when communicating important details.

**Reporting**
Mums on the go don’t necessarily have time to check an app - especially ones who drive. The product must help decide when food is ready and provide a preventative way to stop over/under cooking. The design must reflect state changes; not cooking, programmed to cook, cooking in progress, and cooking finished.

**Suggestions and tracking**
Through planning and creating variance, the product must be universally understandable, to the point that mums can make good decisions around food preparation.  The design must offer intuitive guidance on where information lives and clarity around suggestions based on user behaviour.  

## User journey mapping
Splitting out Sonia's journey with the product experience helped prioritize and focus the design. Post-it notes are a designer's best friend!

- Actions
- Motivations
- Moments of truth (emotions)
- Interactions, touch-points
- Obstacles, pain-points

![Hero image](/images/so_uj.jpg)

**Value Proposition**
To save time. Cook scheduled meals away from home; always ready on time, and cooked to perfection.

## User flow

**Cook dinner for tonight**
This scenario describes the process of putting your meal in the oven, then setting a time to eat and what you've prepared. The other use case when there's no oven interaction but you still want to preheat the oven is out of this project scope. Oven cleanliness reports and settings are a secondary use case that will also live outside the scope of this project.

<div class="fullwidth">
  <img src="/images/so_flow.jpg">
</div>


## Design principles
Based on Sonia’s needs, it was important to outline 3 design principles.

**Direct, task focused**  
The design should move out the way and hand-hold through to successful task completion. Technical jargon around numerical values should be kept to a minimum. Busy mums don't want to do calculations, they’d rather get the job done, and might not have time to explore product features.

**Bold and universal**
Safety is a top concern. Sonia should feel in control and kept in the know about the status of her oven. Clarity around the design is key to quickly understanding oven parameters.

**Useful**
The product should be more utility than content, meant for repeated daily use and provide value efficiently. The core interactions, the ones around oven and hob control, are streamlined, purged of unnecessary questions.

## Ideation
Creating a matrix with feature states and use cases, I was able to focus in on the main problems to solve for.

![Hero image](/images/so_sketch.jpg)

## Wireframes
I iterated on wireframes (v1 to v2) to get task flow feeling natural and intuitive. Adding selected parameters to the flow and keeping things uncluttered were the hardest part of the design process.  

<div class="framed">
  <img src="/images/so_wireframes.jpg">
</div>


## Mocks
First round of design explorations with 2 different colour swatches. Some of the main challenges so far:

1. How not to display the same information twice (time, dish)
2. How to balance alignment left and UI element that didn’t fall under full-width patterns
3. How to keep a consistent colour strategy relevant to the oven states
4. Hierarchy of text, scale and line heights.

<div class="fullwidth">
  <img src="/images/so_mocks1.jpg">
</div>

Some initial tests with the first prototype, and further discussion with another designer led to the following discoveries:

1. The call-to-action affordances aren't clear enough, make it more universal
2. The visual design is bland and without character
3. If you make a mistake, how do you go back
4. the relationship between the oven and what you're doing isn't clear

I built this prototype to understand what was working, and what wasn't.

![Hero image](/images/so_v1.gif)


## Mocks R2
From the first design, I tried to address all four issues:

1. Make CTAs visually more intuitive  
2. Balance colours with layout, leverage icons
3. Implement a stepper to provide clarity and revisions
4. the relationship between the oven and what you're doing isn't clear

<div class="fullwidth">
  <img src="/images/so_mocks2.jpg">
</div>

Using Framer, I quickly put this protoype together.

![Hero image](/images/so_v2.gif)

## Project post mortem

**Didn't work**
Time management was over the allocated 4-6 hours. Since this was a hypothetical project, less time on research and more time on the design seemed a reasonable trade-off. 

**Did work**
Product-market fit and target user needs seemed to hit the right notes for me. By understanding the problem, I was able to focus my design on what the user needed, rather than polluting my scope with other features.

**Do differently**
User testing and prototyping early-on. Given the project constraints, I jumped a few bases to get to a finished state. Handing this to a working mum would have been the cherry on the top!



## Feedback
If you have any feedback or ways to improve this project, please get in touch through any of the social networks on my home page.

<!-- <a href="http://share.framerjs.com/5q3je16uy8z4/" target="_blank">
<button>Play on Framer</button>
</a> -->

<!-- This project is also on <a class="link" href="https://dribbble.com/shots/4336111-Flight-concierge-AI-bot" target="_blank">Dribbble</a> -->
