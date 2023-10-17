---
title: Custom API Gateway services
up:
  - "[[Motis Group]]"
related:
  - "[[Integration architecture design & strategy]]"
  - "[[Migration Services]]"
tags:
  - pattern
date: 2023-10-11
---
The term "data integration", "automation" is an umbrella term that means a lot of things, that don't offer much clarity around what is means for your specific case.

Everyone talks about having ONE place where everything happens.

One pane of glass view.

You can see everything you need to in one window.

You know you need it but you don't really know how it applies to you.

I want to offer an easier framework to understand what data integration is and what we do at Motis Group.

Ultimately what are the integrations that we're building? 

Interoperability.

It means that softwares can talk to each other.

APIs are programmatic ways for softwares to speak with each other BUT understandbly each API is structured differently... 

There needs to be some sort of translation between the two (this is where we get into field mapping).

And then there also needs to be logic (to decide where a piece of data needs to go.) Each branch of logic is in a way a micro-service.  

They're an API Gateway. 

Users are interacting with one or several front end user interfaces and then we're connecting those actions to some backend systems. 

So in that sense we can reframe the term "data integration" and get really specific that what we're building is essentially an advanced data routing mechanism.

We build that API gateway using Tray as the middleware and charging monthly usage fee based on the number of calls routed.