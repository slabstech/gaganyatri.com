---
layout: post
title: "Java interview reference questions"
excerpt: "interview"
categories: jobs
tags: [ jobs ]

date: 2020-11-11T08:08:50-04:00

---

* http://javahungry.blogspot.com/2013/08/hashing-how-hash-map-works-in-java-or.html

* http://javahungry.blogspot.com/2014/06/how-treemap-works-ten-treemap-java-interview-questions.html

* http://javahungry.blogspot.com/2015/02/how-concurrenthashmap-works-in-java-internal-implementation.html

* http://javahungry.blogspot.com/2015/10/how-treeset-works-internally-in-java-interview-questions.html

* http://javahungry.blogspot.com/p/threads.html

* http://javarevisited.blogspot.in/2011/04/synchronization-in-java-synchronized.html

* http://javarevisited.blogspot.in/2011/06/volatile-keyword-java-example-tutorial.html

* http://mrbool.com/working-with-java-executor-framework-in-multithreaded-application/27560

* http://stackoverflow.com/questions/10828863/what-the-use-of-custom-class-loader

* http://stackoverflow.com/questions/10901752/what-is-the-significance-of-load-factor-in-hashmap

* http://stackoverflow.com/questions/11011291/treeset-internally-uses-treemap-so-is-it-required-to-implement-hashcode-method


* http://stackoverflow.com/questions/137975/what-is-so-bad-about-singletons

* http://stackoverflow.com/questions/13855013/understanding-java-memory-management

* http://stackoverflow.com/questions/2087469/sort-a-file-with-huge-volume-of-data-given-memory-constraint

* http://stackoverflow.com/questions/27325997/how-does-countdownlatch-works-in-java

* http://stackoverflow.com/questions/56860/what-is-the-liskov-substitution-principle

* http://stackoverflow.com/questions/8161896/example-code-to-show-how-java-synchronized-block-works

* http://tutorials.jenkov.com/java-concurrency/synchronized.html

* http://tutorials.jenkov.com/java-util-concurrent/cyclicbarrier.html

* http://www.dynatrace.com/en/javabook/how-garbage-collection-works.html

* http://www.oracle.com/webfolder/technetwork/tutorials/obe/java/G1GettingStarted/index.html

* http://www.programcreek.com/2013/03/hashmap-vs-treemap-vs-hashtable-vs-linkedhashmap/

* https://docs.oracle.com/cd/E13150_01/jrockit_jvm/jrockit/geninfo/diagnos/garbage_collect.html

* https://en.m.wikipedia.org/wiki/Creational_pattern

* https://en.wikipedia.org/wiki/SOLID_(object-oriented_design)

* https://lostechies.com/derickbailey/2009/02/11/solid-development-principles-in-motivational-pictures/

* https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design

** Additional Preparation material

Preparation Material:

* You are using a class from a library (say Student). You have a list of Student objects. You need to sort this list based on first name. How will you do it? Constraint: (You do not have the ability to change the source code of the Student class)

* Consider a class Person with two attributes - String name and List<String> degrees. How will you make this class immutable. Ask what are the advantanges of immutable classes

* We have a Parent class with 2 methods walk and run. We have a child class which overrides both the methods. Both child class methods just call their respective Super implementation. Parent class run method calls walk(). class Parent Parent p = new Child(); p.run(); Tell the order in which each method is called

* What is the difference between HashMap and ConcurrentHashMap? Follow up with - what is the difference between CHM and synchronized Map.
* which overloaded method will be called if we pass null as the parameter
* write an sql query to find names of all employees who are having third highest salary
* Given a sorted integer array and a value K. find two elements from given array whose sum will be equal to K
* difference between fail fast and fail safe iterators
* use of volatile keyword
* difference between arraylist and linkedlist
* Consider a class A with a synchronized method class A { public void synchronized m1() {Thread.sleep(5000);} } We create two objects of this class - o1 and o2. We call o1.m1() on one thread and o2.m1() on another thread, at the same time. What will be the behaviour? Follow up with - how will you force these calls to execute one after the other

* We have a Parent class with 2 methods walk and run. We have a child class which overrides both the methods. Both child class methods just call their respective Super implementation. Parent class run method calls walk(). class Parent Parent p = new Child(); p.run(); Tell the order in which each method is called
* Given a List of integers (List<Integer>), write code in Java 8 style to get the sum of the squares of all the odd numbers in the array.
* What is the difference between HashMap and ConcurrentHashMap? Follow up with - what is the difference between CHM and synchronized Map.

*We have a table called BookAuthor. It has two columns Book and Author, Book being unique column. Write a query to find the names of the authors who have written more than 10 books.
* Given an array of n integers and a number k, find the pairs of numbers in the array such that the difference between the pair is k. Find the optimal solution with and without extra storage
* Can one use an Employee class as a key in a HashMap
* Consider a class Person with two attributes - String name and List<String> degrees. How will you make this class immutable. Ask what are the advantanges of immutable classes

* Consider a class A with a synchronized method class A { public void synchronized m1() {Thread.sleep(5000);} } We create two objects of this class - o1 and o2. We call o1.m1() on one thread and o2.m1() on another thread, at the same time. What will be the behaviour? Follow up with - how will you force these calls to execute one after the other
* We have a table called BookAuthor. It has two columns Book and Author, Book being unique column. Write a query to find the names of the authors who have written more than 10 books.
