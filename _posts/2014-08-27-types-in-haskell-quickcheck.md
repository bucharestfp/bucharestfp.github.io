---
layout: default
title: "Types in Haskell; QuickCheck"
date: "2014-08-27 19:00:00"
past: true
edition: "#003"
---

<div class="description">
  <h1><span class="edition-number">#003</span>: Types in Haskell; QuickCheck</h1>
  <p>This meetup took place at the <strong>Eloquentix</strong> office,
    <strong>Wednesday, 27 August 2014</strong> at <strong>19:00</strong>.
    Find out when is our <a href="/next.html">next meetup</a>.</p>
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Enforcing Static Invariants Using Haskell's Type Checker</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Lucian Mogoșanu</h2>
        <h3>Biography</h3>
        <p>Teaching assistant and PhD student at University Politehnica of Bucharest;
        Researcher at VirtualMetrix. Main interest is applying formal and language-based
        methods to verify and prove software systems security.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>
        <p>Haskell is a statically-typed functional programming language: Haskell type
        declarations are identified and checked during compilation, guaranteeing that
        program semantics are known by the designers before execution or possibly even
        before the implementation.</p>
        <p>Additionally, Haskell is strongly-typed, meaning that only explicit type
        conversions are permitted and all program behaviours are defined according to
        the type specification. We intend to explore the features of Haskell's type
        system, using a set of examples as a guide. We also want to use the examples
        to observe its limitations and examine workarounds to help us write correct
        programs.</p>
      </div>
    </div>
    <div class="right">
      <div class="slides">
        Slides in HTML format can be found <a href="#">here</a>.
      </div>
      <div class="recording">
        <iframe width="590" height="442" src="//www.youtube.com/embed/tmgjTWTDnss" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>

<div class="presentation">
  <h1>QuickCheck: First Dive</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Dan Șerban</h2>
        <h3>Biography</h3>
        <p>Dan used to work in enterprise software. Nowadays he is preoccupied with
        Haskell and with all the ways in which it can be made into a practically useful
        tool for the software industry.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>
        <p>Testing individual functions for their natural properties is one of the basic
        building blocks that guides development of large systems in Haskell.</p>
        <p>QuickCheck encourages a high level approach to testing where the developer
        specifies abstract invariants that the algorithms under test should satisfy
        universally, for any input data one might throw at the code. The actual test
        data is automatically generated on behalf of the developer by the testing
        library. In this way the system under test can be hammered with millions of
        tests that would otherwise be infeasible to write by hand, often uncovering
        subtle corner cases that would never have been found through unit testing.</p>
        <p>QuickCheck was created in 1999, and the underlying idea has since been
        implemented to greater or lesser extents and in various shapes in different
        programming languages.</p>
      </div>
    </div>
    <div class="right">
      <div class="slides">
        <script async class="speakerdeck-embed" data-id="7cdb28d0286e0132a0f34a939855d77a" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
      </div>
      <div class="recording">
        <iframe width="590" height="442" src="//www.youtube.com/embed/RneA7Tt3I4U" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>
