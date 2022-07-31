---
layout: page
title: "The Software Architect Elevator - Gregor Hohpe"
excerpt: "Best bits and its implementation "
categories: tldr
tags: [tldr]
modified: 2022-07-30T14:11:53-04:00
---

[Buy Book](https://amzn.to/3ORVNux)

tl;dr
### Ideas Implemented At LeanIX
* IT World is Flat
  * Product vendors core values and philosophy (vendor's world map)
  * What base assumptions did you have to make ?
  * What's the toughest problem you had to solve.
  * Helps to understand whether a vendors and our worldviews align
* Your coffee shop doesn't use two phase commits : Starbucks decoupled barista/cashier
  * Exception Handling - Ignore certain exceptions
  * Retry / Backpressure  - Handled via Github-resilience4j library
  * Asynchronous Transactions over ACID
    * Amazon Order
      * Synchronous Order ID Generation
      * Asynchronous - Billing, Tracking, Delivery, Returns
* Everything in Markdown (engineering blog) and Git/Github - Collaboration
* Agile Manifesto
  * Ship Incrementally
  * Short Lived Daily Branches- faster and clear Code review feedback
  * Spotify Squad Model for Autonomy - Tribes for different functions and products
  * Feedback loop an Autonomy

* Kotlin Blog
  * UML Diagram for Interactions - Plant UML plugin
  * Diagram for Docker multi stage build- Before and now
  * Map Library dependencies
  * jwt.io replacement script
  * Code sample 
  * RFC -sonarqube
  * Feature toggle in pom.xml - klint failonerror:false

### Worth a Read
* Writing for Busy People
* Show the kids the Pirate Ship
* Diagram-Driven Design - UML as sketch

TODO
DDD - Make diagram indicating purpose of each project, How are they connected to S Labs Solutions philosophy


### Books
* [Thinking Fast and Slow, Daniel Kahnemann](https://amzn.to/3zn0AhU)
* [Priceless : The myth of fair value](https://amzn.to/3JxKabv)
* [Foundation of Decision Analysis - Ronald Howard, Ali Abass](https://amzn.to/3zkgCcC)
* [Who needs an Architect, Martin Fowler](https://amzn.to/3oJygSc)
* [The Visual Display of Quantitative  Information, Edward Tuffte](https://amzn.to/3oJ9di4)
* [Enterprise Integration Patterns, Gregor Hohpe](https://amzn.to/3vsdURg)
* [Innovation Games: Creating Breakthrough Products through Collaborative Play, Luke Hohmann](https://amzn.to/3zl0VBR)
* [Technical Writing and Professional Communication, Olsen & Huetin](https://amzn.to/3QaZjBh)
* [Presentation Zen: Simple ideas on Presentation Design and Delivery, Gary Reynolds](https://amzn.to/3OMRKjn)
* [Domain-driven Design: Tackling complexity in the Heart of Software, Eric Evans](https://amzn.to/3JmiVR4)
* [Extreme Programming Explained: Embrace change, Kent Beck](https://amzn.to/3oJyzwk)
* [The Pyramid Principle, Logic in Writing & Thinking, Minto](https://amzn.to/3cNARaR)


### All books
* 
