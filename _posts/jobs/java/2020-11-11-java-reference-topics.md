---
layout: post
title: "Java interview reference questions"
excerpt: "interview"
categories: jobs
tags: [ jobs ]

date: 2020-11-11T08:08:50-04:00

---
https://dzone.com/articles/build-and-package-a-microservices-architecture-wit

https://www.infoq.com/articles/spring-boot-tutorial/



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


[03/11, 19:36] Ad: [23/10, 00:35] Ad: Question and answer

Rating

Comments

You have received a csv file from stock exchange in following format: timestamp, symbol, price, qty, account, buy/sell This file may have millions of records and represents the trading activity for the day. The file is not sorted You need to choose the most optimal collections for holding this data in order to provide analytics efficiently.

* * * * *
took lot of time

Design a new implementation of the Map interface which will also keep a count of all the calls to add a key value pair in the Map. It should count the calls to put, putAll and putIfAbsent methods. The implementation should also be able to provide all the features of any Map implementation that user wants. (e.g. HashMap, TreeMap etc)

* * * * *
Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Ask this question to candidates below 5 years of experience. Create two threads A and B, each printing numbers from 1 to 100 in a sequence. Put a constraint that thread B cannot go ahead of thread A at any point. The threads should operate independently apart from this constraint.

* * * * *
[23/10, 00:37] Ad: Data Structures


Problem Solving




OOPS Concepts


Java Collections


Multi-threading




Design and architecture
[23/10, 09:49] Ad: [23/10, 09:44] Ad: Question and answer

Rating

Comments

You have received a csv file from stock exchange in following format: timestamp, symbol, price, qty, account, buy/sell This file may have millions of records and represents the trading activity for the day. The file is not sorted You need to choose the most optimal collections for holding this data in order to provide analytics efficiently.

* * * * *
took lot of time

Design a new implementation of the Map interface which will also keep a count of all the calls to add a key value pair in the Map. It should count the calls to put, putAll and putIfAbsent methods. The implementation should also be able to provide all the features of any Map implementation that user wants. (e.g. HashMap, TreeMap etc)

* * * * *
Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Ask this question to candidates below 5 years of experience. Create two threads A and B, each printing numbers from 1 to 100 in a sequence. Put a constraint that thread B cannot go ahead of thread A at any point. The threads should operate independently apart from this constraint.

* * * * *
[23/10, 09:45] Ad: We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1
[23/10, 09:45] Ad: You have received a csv file from stock exchange in following format: timestamp, symbol, price, qty, account, buy/sell This file may have millions of records and represents the trading activity for the day. The file is not sorted You need to choose the most optimal collections for holding this data in order to provide analytics efficiently.

* * * * *
Consider the following program to remove negative values from an arraylist: List<Integer> numbers = new ArrayList<>(Arrays.asList(1,24,-1,8,-3,0)); for (Integer i: numbers) If (i<0) numbers.remove(i); } } What is likely to happen? Follow up with a discussion on what this kind of iterator is called and how to resolve this issue.

* * * * *
Design a new implementation of the Map interface which will also keep a count of all the calls to add a key value pair in the Map. It should count the calls to put, putAll and putIfAbsent methods. The implementation should also be able to provide all the features of any Map implementation that user wants. (e.g. HashMap, TreeMap etc)

* * * * *
Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Write a Unix command to give the names of 10 last modified files in the current directory.

* * * * *
Design a Fixed Thread Pool ExecutorService

* * * * *
Ask this question to candidates below 5 years of experience. Create two threads A and B, each printing numbers from 1 to 100 in a sequence. Put a constraint that thread B cannot go ahead of thread A at any point. The threads should operate independently apart from this constraint.

* * * * *
[23/10, 09:46] Ad: Consider the following program to remove negative values from an arraylist: List<Integer> numbers = new ArrayList<>(Arrays.asList(1,24,-1,8,-3,0)); for (Integer i: numbers) If (i<0) numbers.remove(i); } } What is likely to happen? Follow up with a discussion on what this kind of iterator is called and how to resolve this issue.

* * * * *
Stack using Queue

* * * * *
answered

Print tree in spiral fashion

* * * * *
answered.. seems well prepared for interview

What is Semaphore ? Why Synchronization ?

* * * * *
had some idea ..

Sort a Stack with out extra space
[23/10, 09:47] Ad: Design a Fixed Thread Pool ExecutorService

* * * * *
Explain TDD, why TDD is beneficial, discussion on test doubles
[23/10, 09:47] Ad: You have received a csv file from stock exchange in following format: timestamp, symbol, price, qty, account, buy/sell This file may have millions of records and represents the trading activity for the day. The file is not sorted You need to choose the most optimal collections for holding this data in order to provide analytics efficiently.

* * * * *
very confusing and misleading solution

Design a new implementation of the Map interface which will also keep a count of all the calls to add a key value pair in the Map. It should count the calls to put, putAll and putIfAbsent methods. The implementation should also be able to provide all the features of any Map implementation that user wants. (e.g. HashMap, TreeMap etc)
[04/11, 17:23] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Gave an optimal solution using wait() and notifyAll()

Merge m sorted arrays of different sizes (with minimal time and space complexity)
[04/11, 17:24] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number
[04/11, 17:24] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity
[04/11, 17:25] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
Could not answer correctly but approach was correct

We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Suggested a good solution with wait() and notifyAll()

Merge m sorted arrays of different sizes (with minimal time and space complexity)

* * * * *
Suggested an optimal solution with min heap
[04/11, 17:25] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Suggested a decent solution with wait() and notifyAll()

Merge m sorted arrays of different sizes (with minimal time and space complexity)

* * * * *
Couldn't suggest any solution except for sorting
[04/11, 17:25] Ad: Design a class such that only one instance of the class and any of its sub-classes can be created. To clarify: Assume A is such a class and B is derived from A. B does not have any special code apart from extending A new A(); // works fine. new A(); // causes an exception new B(); // works fine as this is the first instance of B new B(); // causes an exception.

* * * * *
We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Merge m sorted arrays of different sizes (with minimal time and space complexity)

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity
[04/11, 17:26] Ad: We have two tables - T1 and T2. Both have a VARCHAR column called ID in both the tables. Write a query to get the count of each ID across both the tables. e.g. T1: | T2: ID | ID --- | --- A | B B | C C | D Expected output: ID ---- A, 1 B, 2 C, 2 D, 1

* * * * *
Print the series 1,2,3,4.... 99 using three threads T1,T2,T3 such that every thread prints every third number

* * * * *
Merge m sorted arrays of different sizes (with minimal time and space complexity)

* * * * *
Change string "all you need is love" to "love is need you all" with constant space complexity
