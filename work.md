---
layout: default
title: Work
permalink: /work/
---

<div class="home">

    <div class="container">
        {% for post in site.work %}

        <div class="post_abstract">

            <a class="post-link" href="{{ post.url | prepend: site.baseurl }}"><h1>{{ post.title }}</h1></a>

            <p>{{ post.blurb }}</p>

            <div>Read more</div>

        </div>

        {% endfor %}
    </div>

</div>