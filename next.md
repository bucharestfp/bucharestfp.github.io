---
layout: default
title: "Software Transactional Memory"
next: true
date: "2016-02-25 19:00:00"
edition: "#019"
permalink: /next/
---

<div class="description">
<!--   <h1>#014: Free Discussions</h1>
  <p>This meetup will take place <strong>Thursday, 27 August 2015</strong> at
    <strong>19:00</strong>.
    <a href="http://www.meetup.com/bucharestfp/events/224710993/"><abbr title="Répondez, S’il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
    <p>No presentation has been scheduled for this meetup, just free discussions.</p>
  <p>See you there!</p> -->
  <h1>#019: Software Transactional Memory</h1>
  <p>This meetup will take place at the <strong>Eloquentix</strong> office,
    <strong>Wednesday, 25 February 2015</strong> at <strong>19:00</strong>.
    <a href="http://www.meetup.com/bucharestfp/events/228604104/"><abbr title="Répondez, S’il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
  <p>See you there!</p>
  <!-- <h1>To be Announced</h1>
  <p>There's no scheduled meetup at the moment, but our tentative date is 19 December 2015.</p>
  <p>Make sure you've registered an account with <a href="http://www.meetup.com/">meetup.com</a>
    and joined <a href="http://www.meetup.com/bucharestfp/">our group</a> there, as that is the
    primary channel for announcing new meetups.</p>
  <p>In addition, you may want to follow our <a href="https://twitter.com/bucharestfp">Twitter account</a>
    and subscribe to our <a href="https://groups.google.com/forum/#!forum/bucharestfp">mailing list</a>.</p>
  <p>See you soon!</p> -->
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Software Transactional Memory</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Dan Șerban</h2>
        <h3>Biography</h3>
        <p>Dan is a data engineer who occasionally teaches advanced functional
        programming, data science (using Spark as the big data framework) and
        full-stack web development. His passion projects are
        <a href="http://lambda.rosedu.org/">"Tweλve days of functional programming"</a>,
        the <a href="http://is.gd/sparkworkshop">Spark Workshop</a> and
        <a href="http://webdevupb.github.io/">WebDev</a>.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>
        <p>Ten years ago, our programs used to be faster when we ran them on a
        next-generation processor, but that time has passed. While that next-
        generation chip will have more cores, each individual core will be no
        faster than the previous year’s model. If we want our programs to run
        faster, we must introduce concurrency into our software designs.</p>

        <p>Conceptually, software transactional memory is a concurrency control
        paradigm analogous to database transactions for controlling access to
        shared memory in concurrent computing. It provides atomic and isolated
        execution for regions of code and is an alternative to lock-based
        synchronization. STM is also the name of a Haskell concurrency library
        implementing the concept, allowing you to share data between threads
        without using locks, removing much of the frustration typical of writing
        threaded code. STM's interface is only slightly more complicated than
        the interface for doing I/O, because it is built around the same core
        monad idea.</p>

        <p>Compared to locks, software transactional memory is a higher-level
        access-control mechanism. From a programmer's standpoint, STM allows you
        to declare what needs to be executed atomically, rather than providing
        explicit instructions. In order to scale, locks require programmers to
        reason about details such as complex fine-grained synchronization and
        deadlock avoidance. Moreover, locks provide only indirect mechanisms
        towards enforcing atomicity and isolation, placing a greater burden on
        the programmer to ensure correctness. Software transactional memory
        promises to automate this process.</p>

        <p>The benefits are composability, easier reasoning about concurrency and
        the absence of deadlocks.</p>

        <p>STM is an optimistic access-control construct, as opposed to the
        pessimism of locks. The general idea of STM is that instead of requiring
        mutual exclusion from an atomic block of code, as would be the case with
        locks, the system allows multiple threads to enter the atomic block of
        code.</p>

        <p>With some bookkeeping of state changes as well as some monitoring for
        the possibility of data races, in the case where a race does not occur,
        the system will allow the threads to commit. Otherwise, at least one
        transaction will be aborted and restarted. In the case where data
        conflicts are rare, this can be a substantial performance gain.</p>

        <p>The core abstraction of Haskell's implementation of STM is the TVar, a
        mutable reference representing general shared state.</p>
      </div>
    </div>
  </div>
</div>

