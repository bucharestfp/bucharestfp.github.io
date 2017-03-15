---
layout: default
title: "Functional Programming Inception"
date: "2017-03-14 19:00:00"
past: true
edition: "#025"
---

<div class="description">
  <h1><span class="edition-number">#025</span>: Functional Programming Inception</h1>
  <p>This meetup took place at the <strong>Adobe</strong> office,
    <strong>Tuesday, 14 March 2017</strong> at <strong>19:00</strong>.
    Find out when our <a href="/next">next meetup</a> is.</p>
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
    <div class="right">
      <p><a href="https://alexn.org/blog/2017/03/15/fp-inception.html">https://alexn.org/blog/2017/03/15/fp-inception.html</a></p>
      <div class="slides">
        <script async class="speakerdeck-embed" data-id="7eeacd81dbf440fba31f024849dbc5c8" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
      </div>
    </div>
  </div>
</div>
