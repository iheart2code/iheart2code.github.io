---
layout: default
title: Work
permalink: /work/
---

<div class="home">

  <div class="container" layout horizontal start wrap around-justified>
    {% for post in site.work %}

    <div class="core_card" layout vertical center center-justified>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    </div>

    {% endfor %}
  </div>

</div>