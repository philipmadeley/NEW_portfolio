---
title: Chatbot concept
description: Flight booking
author: Philip John Madeley
date: 2018-01-20
publishDate: 2018-01-20
# categories: [category 1, category 2]
# tags: [tag 1, tag 2]
comments: false
generatePage: false
img_thumbnail: "images/fb_chatbot.gif"
class: dr_md
draft: false
---

![Hero image](/images/fb_chatbot.gif)

## Overview
AI technologies are still in its infancy, but with advancements in the coming years, we could start to imagine a more tailored 'service' around how we do things. I decided it would be interesting to put that theory to the test through a quick design challenge around booking premium class flight tickets.

## Identifying the target user
Airlines managed to grow premium revenue as a share of total sales on key routes such as the transatlantic, which continues to be the biggest premium air market in the world, and also on flights between Europe and Asia.

* Recent trends with premium class travel
* Carriers want people to pay for premium-class seats.
* Airlines have made it harder to earn miles.
* Some carriers are eschewing first class altogether.
* More international flights (20% 2016) are premium (US*)

![image](/images/fb_chart.jpg)


## User motivation and sentiment

Price isn’t a leading user need. Companies usually pay business class for employees, and PAs often purchase for top-level directors and VPs.

1. <b>Experience</b> (before/during/after)
  includes: Check-in, Airport lounges, Cabin features, Work-related task management, Dinner menu, Service and amenities
2. <b>Time</b>
3. <b>Price</b>

## Direct vs. 3rd party
The experience that accompanies premium travel is the most important user-centric need. Less emphasis is around finding the cheapest ticket, with more emphasis on service, support and status. Some users have negative experiences with 3rd party apps.

![image](/images/fb_compare.jpg)

## User needs statement
John is a frequent business-class traveller from London to North America and S.E Asia.  He expenses travel through his company and uses his flyer miles to upgrade to first class when taking a holiday.  John expects the best in-class service, and needs a way to book  flights through his preferred airlines, understand what his status entitles him to, and see his accumulated miles with various programs. John is relatively tech-savvy and owns both the latest iPhone and Android mobiles. He reads up on fintech news through TechCrunch and downloads new apps regularly.

![image](/images/fb_user.jpg)

## High-level mapping
I decided to focus on going app-direct with destination and dates as the primary user inputs.  Ticket class and passenger details would be solved through onboarding and personalisation. The in-flight experience visual communication should be immersive and not require direct inputs from the user.  Secondary are nice-to-haves, but out of this project scope.

![image](/images/fb_mapping.jpg)

## User journey
John gets an email from his boss to travel to Singapore for a meeting on Wednesday, Feb. 14th.  He must return to London by Friday for another meeting in the afternoon.

1. Receives an email about a meeting
- Opens booking app
- Departure from: London (LHR)
- Destination to: Singapore (SIN)
- Departure arrive by: Feb. 14
- Return arrive by Feb. 16
- Ticket class type: Business
- Airline: Singapore
- Confirms details
- Makes payment
- Gets confirmation email
- Calendar updates

![image](/images/fb_flow.jpg)


## Wireframes
I used crazy 8s to diverge my ideas and looked at different paradigms for selecting and booking flights. For example, input boxes, maps, menus and different interactive forms. For me, the chat paradigm offers an exclusive and tailor-made approach to cater for John’s needs.  


<div class="fullwidth">
  <img src="/images/fb_wireframes.jpg">
</div>

## Visual concept
I used a moodboard to understand the high-level visual concept. The RAF where influential in choosing the main colour.

<div class="fullwidth">
  <img src="/images/fb_moodboard.jpg">
</div>


## Mocks

**Entry point**
1. Enter directly through the app. Other in-points could be an email or notification.
2. A warm welcome focused on your mileage and status. The card recedes to the bottom of the screen if not tapped.
3. Your AI-driven PA picks it up from here, with the last question always fading up but still present if you’d like to go back.

<div class="fullwidth">
  <img src="/images/fb_mocks1.jpg">
</div>


**Selection**
1. The AI offers a presonalised experience. ‘Chips’ populate the bottom and act as your response to the AI.
2. The Chips are versatile and include voice and context-relative icons to activate more complex UI like a date picker.
3. All selected chips remain present at the top right. To go back, tap any chip to jump to that point.

<div class="fullwidth">
  <img src="/images/fb_mocks2.jpg">
</div>

**Check out**
1. Flights are presented in horizontal list form. Icons provide quick context to the experience onboard.
2. Cards expand to full-screen immersive experiences. John can watch videos to see what’s onboard before making a decision.
3. Information is simplified and displayed for confirmation.

<div class="fullwidth">
  <img src="/images/fb_mocks3.jpg">
</div>

## Prototype
The flow includes:
1. Flight destination and time selection
2. Understanding what’s onboard
3. Confirmation and check-out

I used Framer to put this together because I wanted to understand the functionality and granular motion between interactions. Apart from prototyping this experience, during the design stage I tested flows on my mobile as simple click-throughs - which was very useful for understanding the flow!

![Hero image](/images/fb_chatbot.gif)


## Project post-mortem

**Didn’t work**
My solution worked for a couple of choices, however, this isn’t built to scale. The value I placed on offering John an executive experience outweighed the overall usefulness of the UI. In the real-world, an AI that doesn’t nail your expectations will lead to poor UX.  

**Did work**
Breaking the mould with the traditional flight booking interface. From a high-level, the way you respond to questions creates a narrative which maps to a vertical timeline of your activity.

**Do differently**
User testing in the initial stages around basic concepts. The chat paradigm is pretty verbose, and my assumption is that users might just want to jump right into a list view with filters.


## Feedback
If you have any feedback or ways to improve this project, please get in touch through any of the social networks on my home page.

<!-- <a href="http://share.framerjs.com/5q3je16uy8z4/" target="_blank">
<button>Play on Framer</button>
</a> -->

This project is also on <a class="link" href="https://dribbble.com/shots/4336111-Flight-concierge-AI-bot" target="_blank">Dribbble</a>
