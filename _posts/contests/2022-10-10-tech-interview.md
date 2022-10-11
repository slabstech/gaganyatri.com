---
layout: page
title: "Tech interview preparation"
excerpt: "Fine-tuning process"
categories: contests
tags: [ contests ]
date: 2022-10-10T08:08:50-04:00
---

* I/P : GitHub repo with SpringBoot project and maven build tool

* Steps
  * Version Control
    * Fork the repo 
      ````
      gh repo fork slabstech/bhoomi    
      ````
    * Clone the repo 
      ````
      gh repo clone slabstech/bhoomi
      ```` 
    * create development branch
      ```` 
      git checkout -b "feature/sp2-test-setup"
      ````       
  * Maven
    * Compile the project
      ````
      mvn clean install
      ```` 
    * Without test 
      ````
      mvn install -DskipTests 
      ````
    * Run test 
      ````
      mvn test 
      ```` 
  * Continuous Integration - Docker
    * SpringBoot via pom.xml
    * Java 17 - Custom JRE via maven jdk image
    * base alpine-linux image
  * Continuous Deployment - Docker compose
    * SpringBoot 
    * PostgreSQL / PostGIS
  * GitHub Actions
    * TODO
  * Verification of REST API
    * curl
    * postman
  * Create PR to upstream 
    ````
    gh pr create --repo slabstech/bhoomi
    ````
  * 

### References
* fork repo - https://cli.github.com/manual/gh_repo_fork
  * https://docs.github.com/en/get-started/quickstart/fork-a-repo
* clone repo - https://cli.github.com/manual/gh_repo_clone
* Disable tests - https://maven.apache.org/surefire/maven-surefire-plugin/examples/skipping-tests.html
