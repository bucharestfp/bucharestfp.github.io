---
layout: default
title: "Parsing: How Does it Work?"
date: "2016-04-20 19:00:00"
past: true
edition: "#021"
---

<div class="description">
  <h1><span class="edition-number">#021</span>: Parsing: How Does it Work?</h1>
  <p>This meetup took place at the <strong>Eloquentix</strong> office,
    <strong>Wednesday, 20 April 2016</strong> at <strong>19:00</strong>.
    Find out when our <a href="/next">next meetup</a> is.</p>
</div>

<div class="clear-fix"></div>

<div class="presentation">
  <h1>Parsing: How Does it Work?</h1>
  <div class="details">
    <div class="left">
      <div class="biography">
        <h2 class="speaker">Ionuț G. Stan</h2>
        <h3>Biography</h3>
        <p>Ionuț is a software developer at Eloquentix, where he works on backend
        services using Scala. His current interests revolve around functional
        programming techniques, programming languages and compilers.</p>
      </div>
      <div class="abstract">
        <h3>Abstract</h3>

        <p>Transforming text to some in-memory data structure — parsing, as it's
        usually called — is perceived as a form of black magic. It looks like a
        complicated thing to do and parsing an actual programming language even
        more so. It is actually held in such a high regard that some people seem
        to mistake parsing for the task of writing a compiler or interpreter in
        its entirety, which is certainly not the case.</p>

        <p>While not always a trivial task, parsing is probably easier than you
        think and I'll try to prove it during this presentation. We'll see how a
        stream of characters is transformed into a stream of tokens, which are
        then fed to the parser proper that will finally derive an in-memory tree
        data structure. I will be using Scala as the implementation language and
        a subset of Standard ML as the language to parse.</p>
      </div>
      <div>
        <h3>Code</h3>
        <p><a href="https://github.com/igstan/bucharestfp-021">https://github.com/igstan/bucharestfp-021</a></p>
      </div>
    </div>
    <div class="right">
      <div class="slides">
        <script async class="speakerdeck-embed" data-id="e8f16cd22c9847e3b84ff2dc3f4a7a76" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
      </div>
      <div class="recording">
        <iframe width="590" height="442" src="https://www.youtube.com/embed/YQp4DKcd79g" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>
