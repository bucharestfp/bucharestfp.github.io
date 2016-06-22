---
layout: default
title: "Equational Reasoning in Programming"
date: "2016-06-21 19:00:00"
past: true
edition: "#023"
---

<div class="description">
  <h1><span class="edition-number">#023</span>: Equational Reasoning in Programming</h1>
  <p>This meetup took place at the <strong>Eloquentix</strong> office,
    <strong>Tuesday, 21 June 2016</strong> at <strong>19:00</strong>.
    Find out when our <a href="/next">next meetup</a> is.</p>
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Equational Reasoning in Programming</h1>
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
    <div class="right">
      <div class="slides">
        <script async class="speakerdeck-embed" data-id="7773b71b2be24b4fa6fca81743d57b8c" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
      </div>
      <div class="recording">
        <iframe width="590" height="442" src="https://www.youtube.com/embed/B3ElQP1Poxc" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>
