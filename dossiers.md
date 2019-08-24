---
layout: default
title: Dossiers
---

<div class="featured-posts outer">
  <div class="post-feed-title inner">Dossiers</div>
    <div class="post-feed inner-wide">
        {% for post in site.posts %}
          {% if post.dossier == true %}
            {% include postbox.html %}
          {% endif %}
        {% endfor %}
    </div>
</div>