---
layout: default
title: "Equational Reasoning in Programming"
next: true
date: "2016-06-21 19:00:00"
edition: "#023"
permalink: /next/
---

<div class="description">
  <!-- <h1>#014: Free Discussions</h1>
  <p>This meetup will take place <strong>Thursday, 27 August 2015</strong> at
    <strong>19:00</strong>.
    <a href="http://www.meetup.com/bucharestfp/events/224710993/"><abbr title="Répondez, S’il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
    <p>No presentation has been scheduled for this meetup, just free discussions.</p>
  <p>See you there!</p> -->
  <h1>#023: Equational Reasoning in Programming</h1>
  <p>This meetup will take place at the <strong>Eloquentix</strong> office,
    <strong>Tuesday, 21 June 2016</strong> at <strong>19:00</strong>.
    <a href="http://www.meetup.com/bucharestfp/events/231399870/"><abbr title="Répondez, S’il Vous Plaît">RSVP</abbr> on the meetup page</a>,
    where you will also find exact details about this meetup's location.</p>
  <p>See you there!</p>
  <!-- <h1>To Be Announced</h1>
  <p>There's no scheduled meetup at the moment, but our tentative date is 21 June 2016.</p>
  <p>Make sure you've registered an account with <a href="http://www.meetup.com/">meetup.com</a>
    and joined <a href="http://www.meetup.com/bucharestfp/">our group</a> there, as that is the
    primary channel for announcing new meetups.</p>
  <p>In addition, you may want to follow our <a href="https://twitter.com/bucharestfp">Twitter account</a>
    and subscribe to our <a href="https://groups.google.com/forum/#!forum/bucharestfp">mailing list</a>.</p>
  <p>See you soon!</p> -->
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Equational Reasoning in programming</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Mihai Maruseac</h2>
        <h3>Biography</h3>
        <p>Mihai Maruseac is a senior PhD candidate at University of Massachusetts
        Boston. His research focuses on privacy-­preserving publication and
        processing of location data, using techniques such as differential
        privacy and searchable encryption. He holds a Bachelor and a Master
        degree in Computer Science from University "POLITEHNICA" of Bucharest.
        His additional research interests include functional programming and
        artificial intelligence. He is the editor of "Haskell Communities and
        Activities Report", a biannual journal encompassing news in the Haskell
        ecosystem.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>

        <p>Programs in the real world often accumulate technical debt — code that
        is shaped more by its history than its current purpose. Refactoring is
        one way to address that technical debt, making the code simpler, but not
        changing any meaningful behaviour.</p>

        <p>One of Haskell's strengths as a practical language is that it's easy and
        safe to refactor code. It is often said that Haskell is "great for
        equational reasoning", although, perhaps, this is an opaque saying. This
        talk will walk through some examples of that will show how Haskell code
        can be inspected by hand and which will make the isomorphism between
        code execution and interpreting it by substitution become self evident.
        In other words, if one can substitute equals-for-equals then she can
        interpret a Haskell program on pen and paper only.</p>

        <p>In mathematics, calculations are designed to simplify things. In
        contrast, in programming, calculations have different goals, more often
        that of transforming a simple and inefficient program into a more
        efficient but opaque version. The approach taken by Richard Bird in his
        functional pearls, is that of design by calculation: each solution is
        calculated from the problem statement using only the laws of functional
        programming. The Haskell community cares about semantics and laws.
        Referential transparency and the ability to replace equals by equals in
        all contexts allows us to do this kind of calculations to obtain
        efficient programs.</p>
      </div>
    </div>
  </div>
</div>

