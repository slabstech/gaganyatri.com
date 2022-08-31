---
layout: page
title: "Building a SaaS Startup"
excerpt: "Magic of the Cloud"
categories: opensource
tags: [ opensource ]
date: 2022-08-09T08:08:50-04:00
---

### OpenSource Saas MonoRepo , TL;DR

[revive](https://github.com/slabstech/revive) is monorepo that showcases 
1. How to code faster with GitHub Co-Pilot 
2. How to code in the Browser only
3. How GitHub Actions removed the dependency to buy expensive GPU to compile CUDA code.
4. How to build and release Android apk. (TODO)
5. How to publish npm package to npm registry. (TODO)
6. How to publish and Self-host jekyll blog using Jekyll pages (Build Ebook from here)
7. Built Secure Apps with DevSecOps using CodeQL, Dependabots, CI-Jazzer
8. How to build/test/release/deploy Application within minutes using GitHub Actions
9. Build lean Apps with Docker and deploy to DockerHub and GitHub package registry
10. Generate Stripe payment links with Actions for Books/Products. (TODO)
11. Generate Amazon Affiliate links for KindleBooks and Wishlists. (TODO)
12. Periodically publish art snippets to Twitter with tweet-action. (TODO)
13. Use snyk to get notified about vulnerabilities in libraries and plan mitigation (TODO)
14. Setup Infrastructure as Code (TODO)
15. Less Variance in Devices/Setup
16. Increase usage via IDE plugins, ready to use code examples, medium articles
17. Build, Test, --Secure--, Deploy steps with CLI for security - try: ci_fuzz
18. Tutorials with short YouTube videos with tips and tricks (TODO)
19. Showcased the Project at XYZ conference.(TODO)
20. How to publish an ebook
21. How to avoid vendor lock-in with backups
22. Show which distro container is lean and secure
23. Collaborate with new contributors during Hacktoberfest(TODO)
24. Build better with JetBrains OpenSource License support


#### Full Story: How all of its done on the Browser with Zero cost.
* Go to https://github.com/slabstech/revive
* Select use template(Needs to be logged in) to create a repo with revive source code
* Now click settings -> codespaces
  * Select repository -> "username/revive"
    * branch -> main
    * region -> your nearest region
* VSCode IDE on the browser is now setup with "revive" source code
* In VSCode terminal, run ./create_setup.sh 
  * Or ./create_setup.yml config.yml
* Repo is now configured with below configuration
  * Website: jekyll-so-simple theme is deployed with gh-pages-action
    * Code - clients/jekyll/so-simple/website
  * GitHub Actions
    1. [action-cuda-compiler]((https://github.com/slabstech/action-cuda-compiler)) - compile CUDA code for machine learning code, no longer need expensive GPU to start a project
    2. [action-cuda-compiler-python]((https://github.com/slabstech/action-cuda-compiler-python)) - compiles python code for GPU's for pilot projects.
    3. gh-pages-actions for website deployment
    4. action-create-ebook - generate pdf of doc's folder (from markdown or html)
    5. action-deploy-container - creates docker images and upload to GitHub registry and DockerHub
    6. action-chaos-monkey - resilience testing (TODO)
    7. action-secure-fuzz - runs fuzzing logic on inputs with ci_fuzz (TODO)
    8. action-send-tweet - tweets snippets of information based on set frequency (TODO)

* How to avoid vendor lock-in
  * By having redundant backups of public infrastructure at gitlab, bitbucket (inspired by Google copybarra service to copy code from one repository to another)
  * Create [action-backup-repo](https://github.com/slabstech) (TODO)
* Show which distro container is lean and secure
  * Both alpine-linux and Google's distroless container are of similar size. [Check Test](https://github.com/slabstech/docker)
  * Need to verify security credentials for each container
  * Test 
    * Time to build
    * Community usage
    * Example code in Production
* Follow [project roadmap](https://github.com/orgs/slabstech/projects/1) for revive sprint tasks

* How to conduct Hacktoberfest
  * Create simple Issues/Request from Project roadmap.
  * Add contribution guidelines and conditions to be met to participate in Hacktoberfest.
  * Create a Hacktoberfest campaign and add it to the project roadmap.
  * Create a Repo - Hacktoberfest
    * Create folder for 2022
      * Contributors get a readme file with their github username for adding their PR and intro.
      * Ex. sachinsshetty.md : 
        * Description : Created PR in bhoomi project for weather info.
        * Bio : Open Sourcerer and DIYer.
  * Create Hacktoberfest event - Participate in the month long celebration
    * Hacktoberfest '21  from DigitalOcean - [Website](https://hacktoberfest.digitalocean.com/)
    * GitHub’s guide to Hacktoberfest 2021  - [GitHub Blog Post](https://github.blog/2021-10-07-githubs-guide-hacktoberfest-2021/)
    * Add revive project to - Hacktoberfest topic - [GitHub](https://github.com/topics/hacktoberfest) 


---
### TODO 
* Create client-side UI which generates config.yml for Revive repo 
  * Idea is similar to start.spring.io 
* Choose setup
  * Website - Jekyll theme
    * so-simple
    * minimal- mistakes
  * Database - postgreSQL
  * Server _
    * Dropwizard
    * Spring Boot
  * Languages
    * Kotlin
    * Java
    * Java + Kotlin
  * Docker
    * Java 17 - Custom JRE
    * PostgreSQL - 14.x
* Create end-to-end Code Example to demonstrate how to use Revive's GitHub Actions


---
1. How to publish an ebook
  [Action - action-create-ebook](https://github.com/slabstech/action-create-ebook)
2. How to code in the Browser
   * With codespaces - Code from Anywhere.
3. How GithubActions removed the dependency to buy expensive GPU for compile code.
  * [cpp compiler](https://github.com/slabstech/action-cuda-compiler)
  * [python compiler](https://github.com/slabstech/action-cuda-compiler-python)
4. How to build and release Android apk (TODO)
  * [Action - actoion-generate-publish-android-apk](https://github.com/slabstech/)
5. How
6. How



-- Extra to edit
* Create Diagrams + UI - Reduce text information - Information overload
* Github Registry -
  * How I saved on public code cost using Github Packages and
  * Released Android APK without spending a rupee.

Read the precursor session - [Leveraging OpenSource to Bootstrap an Idea](https://gaganyatri.com/opensource/leveraging-opensource/)

