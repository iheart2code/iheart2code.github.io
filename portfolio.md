---
layout: default
title: Portfolio
permalink: /portfolio/
---

<div class="home">

  <div class="container" layout horizontal start wrap around-justified>
    {% for post in site.posts %}

    <div class="core_card" layout vertical center center-justified>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </div>

    {% endfor %}
  </div>

</div>