---
layout: default
---

<div class="archive">
  <div class="next">
    <h2>Next</h2>
    <ol>
    {% for post in site.pages %}
      {% if post.next %}
      <li><span>{{ post.edition }} &middot; <time>{{ post.date | date: "%b %d, %Y" }}</time> &middot;</span>
        <a href="{{ '/next/' | prepend: site.baseurl }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
    </ol>
  </div>

  <div class="past">
    <h2>Past</h2>
    <ol>
      {% for post in site.posts %}
        {% if post.past %}
        <li>
          <span>{{ post.edition }} &middot;
            <time title="{{ post.date }}">{{ post.date | date: "%b %d, %Y" }}</time> &middot;</span>
          <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </li>
        {% elsif post.cancelled %}
        <li>
          <span>{{ post.edition }} &middot;
            <time title="{{ post.date }}">{{ post.date | date: "%b %d, %Y" }}</time> &middot;</span>
          Beer and Discussions
        </li>
        {% endif %}
      {% endfor %}
        <li><span>#001 &middot; <time>Jul 20, 2010</time> &middot;</span> Beer and Discussions</li>
        <li><span>#000 &middot; <time>Jun 10, 2010</time> &middot;</span> Beer and Discussions</li>
    </ol>
  </div>
</div>
