---
layout: page
title: "How we are Lean(IX)? - Adopting Best Practices from : Software Architect Elevator - Gregor Hohpe"
excerpt: "Best bits and its implementation "
categories: tldr
tags: [tldr]
modified: 2022-07-30T14:11:53-04:00
---

Read below to what I observed and related from the amazing book by Gregor Hohpe. (75% Summary)
[The Software Architecture Elevator - Buy Book](https://amzn.to/3ORVNux)

"Digital transformation is driven by Democratization", that is giving everyone rapid access to resources.

With SSO(Single Sign on Policy) all services are available instantly, 

Easter Egg - my fellow new joinee, found out that we dont depend on vendor locked-in tools . By utilising and contributing to open source tools
we avoid vendor lock-in and help other companies to accelerate IT transformation

### Chapters
* 39 - Who likes standing in the queue
  * Queuing theory - Computability , Single Queue, Muliple Server Systems
  * Looking between activities - Reduce wait times than utlization
  * Finding Queues
    * Busy Calendars
    * Steering Meetings
    * Software Releases
    * Email
    * Workflow
  * Making Queues Visible
* 38 - 

tl;dr
### Ideas Implemented At LeanIX
* Infrastructure as Code
* Your coffee shop doesn't use two phase commits : Starbucks decoupled barista/cashier
* Everything in Markdown (engineering blog) and Git/Github - Collaboration
* Agile Manifesto
* IT World is Flat
* They Dont build 'em quite like that anymore
* Governance - Why we have different MacBooks

### Additional Chapters - A Glance 
* Writing for Busy People
* Show the kids the Pirate Ship
* Diagram-Driven Design - UML as sketch

Most of the engineering practices of LeanIX are seen in the book, my questions to the team were answered by the Book.
 
### Full Story Here
* Infrastructure as Code
  * Access control to project is via Pull Requests. Via [Codeowner](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) file
* They Dont build 'em quite like that anymore
  * Autonoumous tribes over rigid pyramid organsiation structures
  * Avoid inverse pyramid . reduce dependency on External solution providers
  * Building modern structures - Reusable components/Similar functionality is provided to base layer infrastructure to reduce redundant work  
* Your coffee shop doesn't use two phase commits : Starbucks decoupled barista/cashier
  * Exception Handling - Ignore certain exceptions
  * Retry / Backpressure  - Handled via Github-resilience4j library
  * Asynchronous Transactions over ACID
    * Amazon Order
      * Synchronous Order ID Generation
      * Asynchronous - Billing, Tracking, Delivery, Returns
* Everything in Markdown (engineering blog) and Git/Github - Collaboration
* Agile Manifesto
  * Ship Incrementally - Complete Utilisation of Github DevOps
  * Short Lived Daily Branches- faster and clear Code review feedback
* Autonomy
  * Self-reliant teams
  * Spotify Squad Model for Autonomy - Tribes for different functions and products
  * Feedback loop an Autonomy
* IT World is Flat
  * Customer Success Teams
  * Product vendors core values and philosophy (vendor's world map)
  * What base assumptions did you have to make ?
  * What's the toughest problem you had to solve.
  * Helps to understand whether a vendors and our worldviews align
* Governance
  * Please read page 264 on why we have different MacBook models.


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



//TODO 

Part 1

Dangers of riding the architecture elevator

Designing for the first derivative

Micromort - Decision analysis