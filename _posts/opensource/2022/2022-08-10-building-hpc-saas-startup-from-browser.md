---
layout: page
title: "Building a SaaS Startup with only a Browser"
excerpt: "Magic of the Cloud"
categories: opensource
tags: [ opensource ]
date: 2022-08-09T08:08:50-04:00
---

### OpenSource Saas MonoRepo , TL;DR

[revive](https://github.com/slabstech/revive) is monorepo that showcases 
1. How to publish an ebook 
2. How to code in the Browser
3. How GithubActions removed the dependency to buy expensive GPU for compile code.
4. How to build and release Android apk. (TODO)
5. How to publish npm package to npm registry. (TODO)
6. How to publish and Self-host jekyll blog using Jekyll pages (Build Ebook from here)
7. Built Secure Apps with DevSecOps using CodeQL, Dependabots, CI-Jazzer
8. How to build/test/release/deploy Application within minutes using Github Actions
9. Build lean Apps with Docker and deploy to DockerHub and GitHub package registry
10. Generate Stripe payment links with Actions for Books/Products. (TODO)
11. Generate Amazon Affiliate links for KindleBooks and Wishlists. (TODO)
12. Periodically publish art snippets to Twitter with tweet-action. (TODO)
13. Use snyk to get notified about vulnerabilites in libraries and plan mitigation (TODO)

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
  * Github Actions
    1. gh-pages-actions for website deployment
    2. action-create-ebook - generate pdf of doc's folder (from markdown or html)
    3. action-deploy-container - creates docker images and upload to GitHub registry and DockerHub
    4. action-chaos-monkey - resilience testing (TODO)
    5. action-secure-fuzz - runs fuzzing logic on inputs with ci_fuzz (TODO)



* Follow [project roadmap](https://github.com/orgs/slabstech/projects/1) for revive sprint tasks

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
* 
* Github Registry -
  * How I saved on public code cost using Github Packages and
  * Released Android APK without spending a rupee.

Read the precursor session - [Leveraging OpenSource to Bootstrap an Idea](https://gaganyatri.com/opensource/leveraging-opensource/)

