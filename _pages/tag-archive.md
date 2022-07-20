---
title: "Posts by Tag"
permalink: /tags/
layout: archive
author_profile: true
---

<section id="publications">
<h2>Publications</h2>

{% for tag in tags %}
<section id="{{ tag | slugify | downcase }}" class="taxonomy__section">
    <h3 class="archive__subtitle">{{ tag }}</h3>
    <div class="entries-{{ entries_layout }}">
        {% for post in site.publications %}
        {% if post.tags contains tag %}
            <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
        {% endif %}
        {% endfor %}
    </div>
    <a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }}
        &uarr;</a>
</section>
{% endfor %}
</section>

<!-- <h2 id="publications">Blogs</h2>

{% assign tags =  site.posts | map: 'tags' | join: ','  | split: ',' | uniq %}
{% for tag in tags %}
  <h3>{{ tag }}</h3>
  <ul>
  {% for post in site.posts %}
    {% if post.tags contains tag %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
  </ul>
{% endfor %} -->
