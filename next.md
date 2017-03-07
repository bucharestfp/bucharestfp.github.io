---
layout: default
title: "Functional Programming Inception"
next: true
date: "2017-03-14 19:00:00"
edition: "#025"
permalink: /next/
---

<div class="description">
  <!-- <h1>#014: Free Discussions</h1>
  <p>This meetup will take place <strong>Thursday, 27 August 2015</strong> at
    <strong>19:00</strong>.
    <a href="http://www.meetup.com/bucharestfp/events/224710993/"><abbr title="Répondez, S'il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
    <p>No presentation has been scheduled for this meetup, just free discussions.</p>
  <p>See you there!</p> -->
  <h1>#025: Functional Programming Inception</h1>
  <p>This meetup will take place at <strong>Adobe</strong>,
    <strong>Tuesday, 14 March 2017</strong> at <strong>19:00</strong>.
    <a href="https://www.meetup.com/bucharestfp/events/238236715/"><abbr title="Répondez, S'il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
  <p>See you there!</p>
  <!-- <h1>To Be Announced</h1>
  <p>There's no scheduled meetup at the moment, but our tentative date is 20 July 2016.</p>
  <p>Make sure you've registered an account with <a href="http://www.meetup.com/">meetup.com</a>
    and joined <a href="http://www.meetup.com/bucharestfp/">our group</a> there, as that is the
    primary channel for announcing new meetups.</p>
  <p>In addition, you may want to follow our <a href="https://twitter.com/bucharestfp">Twitter account</a>
    and subscribe to our <a href="https://groups.google.com/forum/#!forum/bucharestfp">mailing list</a>.</p>
  <p>See you soon!</p> -->
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Functional Programming Inception</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Alexandru Nedelcu</h2>
        <h3>Biography</h3>
        <p><a href="https://alexn.org/">Alexandru Nedelcu</a>, <a href="https://github.com/alexandru">@alexandru</a>
        on GitHub/Gitter and <a href="https://twitter.com/alexelcu">@alexelcu</a> on Twitter,
        is the lead developer of the <a href="https://monix.io/">Monix</a> library.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>

        <p>Designing functionality that exhibits the properties of functional
        programming is hard because it requires a mentality change, coping with
        immutability and consideration for recursion, performance and
        polymorphism. This talk is a lesson in FP design that makes use of
        Scala's hybrid OOP+FP nature.</p>

        <p>We are going to start from Scala's (and Java's) ubiquitous
        Iterator/Iterable types which expose the famous iterator pattern,
        analyzing its strengths and weaknesses. And then we are going to work
        our way up to a fully featured FP replacement that has referential
        transparency and that fixes everything that's wrong with Iterator, while
        being more generic.</p>

        <p>This lesson in design involves talking about immutability, imperative
        programming, asynchrony and problems encountered when going FP, like
        performance considerations, recursion and memory leaks. We are also
        going to talk about ADTs, higher kinded polymorphism and type-classes
        versus OOP subtyping. Interestingly the example presented will use both
        OOP subtyping and type-classes and thus we can make a clear comparison
        about what to use and when - a problem that the Scala developer has in
        his daily work.</p>

        <p>A working knowledge of the Scala programming language is required.
        Knowledge about Scala's Future or the Task data type in Monix or from
        Scalaz is recommended, but not required.</p>
      </div>
    </div>
    <div class="right"></div>
  </div>
</div>
