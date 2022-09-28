---
layout: post
title: "Improve Scores in Code Challenges"
excerpt: "Understanding the pattern"
categories: contests
tags: [ contests ]
date: 2022-09-27T08:08:50-04:00
---

A pattern to observe in code challenges, is how inputs are created
and how code is validated against generated additional inputs.

The solution to improve scores is to generate extreme/edge cases ourselves
and test it with "Run/Test" option to cover all cases, before submitting the solution
to the platform.

What we are proposing is known as TDD/Test driven development in software engineering.

Before writing/attempting the solution code, we should first identify the
probable inputs, expected outcomes, handling erroneous/missing data. Then we write
our assertions/expectation in the Tests, such that any new code/modifications/refactoring does
not change the essence/objective of the project/solution.

Test containers can be used for system requirements and end-user configs are replicated and tested
via code on each commit. Another approach for solving input parameters generation is utilising
the concept of Fuzzing. Fuzz tests generate a wide range of inputs to identify design issues
in edge cases.

At the "Revive-puzzles" library project were incorporating the above techniques to make code
more robust and simulate actual scenarios.
