---
layout: page
title: "Leveraging OpenSource to Bootstrap an Idea"
excerpt: "Race of the Blocks"
categories: opensource
tags: [ opensource ]
date: 2022-08-09T08:08:50-04:00
---

Read my session entry for [GithubUniverse](https://gaganyatri.com/opensource/building-hpc-saas-startup-from-browser/)

Agenda
* Show How GitHub is useful with 
  * GitHub Enterprise ([LeanIX](https://github.com/leanix)) and 
  * GitHub Free Tier ([sachinsshetty](https://github.com/sachinsshetty))

* GithubActions and its usefulness (Available as public repo's)
  * Secrets management via Kubernetes
    * [secrets-action](https://github.com/leanix/secrets-action)
  * Kubernetes
    * [k8s-connector](https://github.com/leanix/leanix-k8s-connector)
    * [k8s-deploy](https://github.com/leanix/k8s-deploy-action)
  * Dockerized Application deployment ([Java 17 - Custom JRE](https://github.com/slabstech/revive))
    * [release-docker-image](https://github.com/leanix/release-docker-image-action)
  * Full CI/CD and multiple deploys using custom Github Actions (also OpenSourced)
    * [storage-deploy](https://github.com/leanix/storage-deploy-action)

* Workshop/ Demo
    * Demonstrate an example Dropwizard project (Best Practices - Create a blog post ?? )
      * [revive](https://github.com/slabstech/revive)
    * Resilience and Scaling using Kubernetes
      * Build a mini-kube cluster using Raspberry-Pi and show deployment end-to-end
      * Use HomeOffice Budget ? To build setup for on-premise Kubernetes cluster
      * Test different scenarios of Chaos Monkey 
    * For kids to be attracted, attach RGB, which shows deployment status and greets them on a terminal.

* Hiring Challenge
    * Simple puzzle, those who cross the threshold score get an interview invite.
    * Top Scorer during the event, gets to Win a prize (Maybe a replacement for the raffle / Or additional prize if budget supports it)
    * Something like comma.ai hiring challenge . https://github.com/commaai/calib_challenge 
      * TicTacToe Puzzle from [LeanIX Dev Con](https://github.com/leanix/leanix-dev-conf) (Needs update)
