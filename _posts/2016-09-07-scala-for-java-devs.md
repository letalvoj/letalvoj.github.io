---
layout: post
title:  "FP in Scala for Java developers!"
date:   2016-09-07 12:50:01 +0200
categories: scala
---
Soon I'll present a series of informal _small talks_ on advanced topics in functional programing in Scala.
The point is not to teach you everything I've learned so far but rather to show you what I think it might be important for you as Java developers while transitioning to Scala.
I will assume that you've already underestood basic Scala syntax.
Therefore if you have not yet then please check _one of the following resources_:

 * *If you have several days*: [Odersky's course on Coursera](https://www.coursera.org/learn/progfun1)
 * *If you have an hour:* [Official scala-lang blog post](http://docs.scala-lang.org/tutorials/scala-for-java-programmers.html)
 * Or any other online resource. Maybe you'll find some nice youtube video.

## What are we going to cover

The motivation behing those talks is to avoid misusing Scala just as a _nice version of Java_.
I'll try to cover these fundamental FP topics:

 * Scala type system and implicits
 * Recursion, tail recursion, and folds
 * Data types
   * *error handling:* Validated, Xor, Option, ...
   * *fp:* State, Kleisli, ...
 * Type classes
   * *basic algebraic structures:* Semigroup, Monoid, ...
   * *fp:* Functors, Monads, Applicatives, ...

As a reference I recommand you the [Functional Programming in Scala by Paul Chiusano](https://www.amazon.com/Functional-Programming-Scala-Paul-Chiusano/dp/1617290653/).
During the whole time we'll use the [cats](http://typelevel.org/cats/typeclasses.html) library for which there is a great [herding-cats tutorial](http://eed3si9n.com/herding-cats/) online.

## Organization

During a two week period we'll loosely follow the herding-cats tutorial enriched with theory from the red book.
Each day you'll be asked to implement a simple assignment to demonstrate elementary underestanding of the covered topic.
If required I'll publish all necesseary sources in a special github repository.
